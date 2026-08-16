# SPRING MVC 

**Order Management Application**

### Objective

Develop a web-based **Order Management Application** using Spring MVC.

---

## Problem Statement

A company requires a simple web application to manage customer orders.

The application should allow the user to perform the following operations:

1. Add a new order
2. Retrieve order details
3. Update an existing order
4. Delete an existing order

The application should provide suitable web pages for performing these operations.

---

## Order Details

Each order should contain the following information:

* Order ID
* Customer Name
* Product Name
* Quantity
* Price
* Order Status

---

## Functional Requirements

### 1. Add Order

Provide a form through which the user can enter the order details and add a new order.

The application should prevent duplicate Order IDs.

---

### 2. Retrieve Order

Provide functionality to:

* Display all orders
* Retrieve a particular order using Order ID

If the requested order does not exist, display an appropriate message.

---

### 3. Update Order

Allow the user to modify the details of an existing order.

The user should be able to update:

* Customer Name
* Product Name
* Quantity
* Price
* Order Status

The Order ID should not be changed during the update.

---

### 4. Delete Order

Allow the user to delete an order using its Order ID.

If the specified Order ID does not exist, display an appropriate message.

---

## Sample Order Data

The application may start with sample orders such as:

| Order ID | Customer | Product    | Quantity | Price | Status    |
| -------- | -------- | ---------- | -------: | ----: | --------- |
| 1001     | Rahul    | Laptop     |        2 | 55000 | CONFIRMED |
| 1002     | Priya    | Mobile     |        1 | 30000 | PLACED    |
| 1003     | Arjun    | Headphones |        3 |  5000 | SHIPPED   |

Students may use their own sample data.

---

## Technical Requirements

The application must be developed using **Spring MVC**.

The following concepts covered in the module should be demonstrated appropriately in the application:

* Spring MVC configuration
* `DispatcherServlet`
* Controllers
* `@Controller`
* `@RequestMapping`
* `ModelAndView`
* ViewResolver
* `InternalResourceViewResolver`
* XML-based configuration
* JSP views
* MySql Database

-------


## Expected Operations

The completed application must successfully perform:

```text
ADD
RETRIEVE
UPDATE
DELETE
```

All operations should be accessible through the web interface.

---

 

### Note

Students are expected to design the application structure and implement the Spring MVC request handling based on the concepts covered in the module.

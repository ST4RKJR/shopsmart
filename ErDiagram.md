# ER Diagram Documentation

## Overview

This document describes the Entity-Relationship (ER) structure of the E-Commerce Website project.

## Main Entities

### 1. User

* user_id (Primary Key)
* name
* email
* password
* role (customer/admin)

### 2. Product

* product_id (Primary Key)
* name
* description
* price
* stock
* category_id (Foreign Key)

### 3. Category

* category_id (Primary Key)
* category_name

### 4. Cart

* cart_id (Primary Key)
* user_id (Foreign Key)

### 5. Order

* order_id (Primary Key)
* user_id (Foreign Key)
* order_date
* total_amount
* status

### 6. OrderItem

* order_item_id (Primary Key)
* order_id (Foreign Key)
* product_id (Foreign Key)
* quantity

## Relationships

* One User can place many Orders.
* One Order can have many OrderItems.
* One Product belongs to one Category.
* One User has one Cart.
* One Cart can contain multiple Products.

This ER structure ensures proper data organization and scalability.

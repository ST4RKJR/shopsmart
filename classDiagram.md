# Class Diagram Documentation

## Overview

This document describes the main classes used in the E-Commerce Website project.

## Main Classes

### 1. User

Attributes:

* userId
* name
* email
* password
* role

Methods:

* register()
* login()
* logout()

### 2. Product

Attributes:

* productId
* name
* description
* price
* stock

Methods:

* updateStock()
* applyDiscount()

### 3. Cart

Attributes:

* cartId
* userId
* items

Methods:

* addItem()
* removeItem()
* calculateTotal()

### 4. Order

Attributes:

* orderId
* userId
* orderDate
* totalAmount
* status

Methods:

* createOrder()
* updateStatus()

These classes represent the core structure of the application and can be implemented using TypeScript.

# Sequence Diagram Documentation

## Overview

This document describes the sequence flow for key operations in the E-Commerce Website.

## 1. User Login Process

1. User enters email and password.
2. Frontend sends login request to backend.
3. Backend verifies credentials from database.
4. Backend returns success or failure response.
5. User is redirected to dashboard if successful.

## 2. Add to Cart Process

1. User clicks "Add to Cart".
2. Frontend sends product ID to backend.
3. Backend updates cart in database.
4. Backend returns updated cart response.
5. Frontend updates cart UI.

## 3. Place Order Process

1. User clicks "Checkout".
2. Frontend sends order details to backend.
3. Backend creates order record.
4. Payment is processed.
5. Order confirmation is sent to user.

These sequences show how frontend, backend, and database interact.

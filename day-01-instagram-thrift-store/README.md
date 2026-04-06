# 📦 Day 1: Instagram Thrift Store Database Design

## 🧠 Problem

A small creator sells thrifted and handmade fashion items through Instagram DMs and WhatsApp.

The goal is to design a database to:

* Manage products
* Track inventory
* Handle orders
* Store payment details

## 🔥 Key Challenges

* Thrift items are unique (only one piece)
* Handmade items can have multiple units
* Orders are not from a traditional website

## 💡 Solution

* Used a separate `inventory` table to handle:

  * Size
  * Color
  * Quantity

* Used `order_items` as a junction table:

  * One order → multiple products

* Payment tracked separately

## 🧱 Entities

* Customers
* Products
* Inventory
* Orders
* OrderItems
* Payments

## 🚀 Learning

This helped me understand:

* Real-world database thinking
* Avoiding over-engineering
* Handling unique vs multi-stock products

---

Day 1 complete ✅

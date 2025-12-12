# food-ordering-management-system-c
This project is a full-featured Food Ordering &amp; Delivery Management System written in C. It includes user authentication, menu management, cart operations, promo codes, and order processing using Stack and Priority Queue. Delivered orders are stored using AVL Tree, and users are managed using BST. Designed for academic and learning purposes
# 🍔 Food Ordering & Delivery Management System (C Project)

A complete **Food Ordering & Delivery Management System** written in C, using advanced data structures such as:

- Singly Linked List (Menu)
- Doubly Linked List (Cart & Order Items)
- Stack (Pending Orders)
- Queue (Delivery System)
- BST (User Management)
- AVL Tree (Order History)
- Circular Linked List (Promo Codes)

This project simulates a real-world online food ordering platform with user login, admin panel, order processing, delivery queue, promo codes, priority system, and data persistence.

---

## 🚀 Features

### 🧑‍🍳 **User Features**
- User Sign Up & Login (Stored in a BST)
- Browse Menu by Category
- Add/Remove items from Cart (Doubly Linked List)
- Apply Promo Codes (Circular Linked List)
- Place Order with Priority Levels:
  - Low
  - Normal
  - High
  - Express
- Track Order Status
- View Order History (AVL Tree based)
- Loyalty Points System

---

### 🛠️ **Admin Features**
- Add Food Items to Menu (Singly Linked List)
- View All Users (BST Traversal)
- Process Orders (Stack)
- Manage Delivery Queue (Priority-based Queue)
- Update Order Status
- Manage Promo Codes
- View Order History (AVL Tree)

---

### 📦 **Order Processing Workflow**
1. User adds items to cart  
2. User checks out  
3. Order saved in **Stack**  
4. Admin pops stack → processes order  
5. Order moved to **Delivery Queue**  
6. Delivery queue sorted by priority  
7. Delivered orders stored in **AVL Tree (History)**  

---

## 🧵 Data Structures Used

| Feature | Data Structure | Reason |
|--------|----------------|--------|
| Menu | Singly Linked List | Fast append + traversal |
| Cart | Doubly Linked List | Forward/backward deletion |
| Promo Codes | Circular Linked List | Infinite cycling of codes |
| Users | Binary Search Tree | Sorted storage + fast search |
| Order Items | Doubly Linked List | Easy modifications |
| Pending Orders | Stack | LIFO processing |
| Delivery Queue | Priority Queue (Linked) | High priority first |
| Order History | AVL Tree | Balanced + fast search |

---

## 📁 File Structure


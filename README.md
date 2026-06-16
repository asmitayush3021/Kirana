# 🛒 Kirana

### 🚀 Modern Commerce Platform with Integrated Customer Support

Northwind Store is a full-stack commerce platform built to solve the problem of fragmented post-purchase customer experiences. Traditional e-commerce businesses often rely on separate tools for payments, order management, customer support, file sharing, and live assistance, creating operational overhead and friction for customers.

This platform unifies the entire customer journey—from product discovery and checkout to order tracking, real-time support, and video consultations—within a single application. Customers can purchase products, monitor orders, communicate with support teams, share files, and join live support sessions directly from their order portal without switching between multiple platforms.

---

## ✨ Features

### 🛍️ Customer Experience

* Browse and discover products
* Product categorization and filtering
* Product detail pages
* Shopping cart management
* Secure checkout experience
* Order history and tracking
* Responsive user interface

### 💳 Payments & Orders

* Polar payment integration
* Webhook-driven order fulfillment
* Secure checkout sessions
* Automated order creation
* Order status management
* Persistent order history

### 💬 Real-Time Customer Support

* Dedicated order-specific support channels
* Real-time messaging using Stream Chat
* Typing indicators
* Message reactions
* Threaded conversations
* File sharing
* GIF support
* Customer-support communication history

### 📹 Live Video Assistance

* One-click video consultation requests
* Order-linked support calls
* Real-time customer assistance
* Stream Video integration

### 🔐 Authentication & Authorization

* Secure authentication with Clerk
* Role-based access control
* Customer, Support, and Admin roles
* Protected routes and APIs

### 🛠️ Admin Dashboard

* Product management
* Product creation and updates
* Product activation/deactivation
* Image management
* Administrative controls

### 📤 Media Management

* Image uploads via ImageKit
* Optimized media delivery
* Secure asset management

### 📊 Monitoring & Reliability

* Error tracking with Sentry
* Performance monitoring
* Structured logging
* Production-ready observability

---

## 🎯 Problem Solved

Many online businesses use separate systems for payments, order management, customer support, and live customer assistance. This fragmented workflow forces customers and support teams to switch between multiple tools, leading to slower issue resolution and a poor post-purchase experience.

Northwind Store addresses this challenge by providing a unified commerce and customer-support platform where purchasing, order tracking, real-time communication, and live assistance coexist within a single workflow, improving customer satisfaction while reducing operational complexity.

---

## 🏗️ Architecture

```text
Customer
   │
   ▼
React Frontend
   │
   ▼
Express + TypeScript API
   │
   ├── PostgreSQL (Drizzle ORM)
   ├── Clerk Authentication
   ├── Polar Payments
   ├── Stream Chat & Video
   ├── ImageKit
   └── Sentry Monitoring
```

---

## 🛠️ Tech Stack

### Frontend

* ⚛️ React
* ⚡ Vite
* 🎨 Tailwind CSS
* 🌼 DaisyUI
* 🔄 TanStack Query
* 🗂️ Zustand
* 🔐 Clerk

### Backend

* 🟢 Node.js
* 🚂 Express.js
* 📘 TypeScript
* 🗄️ PostgreSQL
* 🧩 Drizzle ORM
* ✅ Zod Validation

### Integrations

* 💳 Polar Payments
* 💬 Stream Chat
* 📹 Stream Video
* 📤 ImageKit
* 🚨 Sentry

### Deployment

* 🐳 Docker
* ☁️ Cloud-ready Architecture

---

## 🚀 Key Impact

Northwind Store transforms a traditional online store into a customer engagement platform by integrating commerce, support, and live assistance into a single ecosystem. The result is a seamless post-purchase experience that improves support responsiveness, reduces customer friction, and enables businesses to manage customer interactions from one centralized platform.

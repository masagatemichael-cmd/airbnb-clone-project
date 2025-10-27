# Airbnb Clone Project

## 🏡 Overview
This project is an Airbnb clone that allows users to book, list, and manage rental properties. The goal is to replicate core Airbnb functionalities while learning modern web development practices.

## 🎯 Project Goals
- Build a scalable full-stack application
- Practice authentication, database design, and API development
- Learn deployment and DevOps basics

## 🧰 Technology Stack

### Frontend
- **Next.js**: A React framework that supports server-side rendering and static site generation for better performance and SEO.
- **React**: A JavaScript library for building user interfaces using reusable components.
- **Tailwind CSS**: A utility-first CSS framework for quickly styling applications.

- ## Team Roles

## 🗄️ Database Design

The project’s database is structured around five main entities: **Users**, **Properties**, **Bookings**, **Reviews**, and **Payments**.  
These entities work together to manage listings, reservations, and user interactions within the Airbnb clone.

---

### 🧍 Users
**Purpose:** Represents users who can either host properties or book stays.

**Key Fields:**
- `id` – unique identifier for each user  
- `name` – user’s full name  
- `email` – user’s email (unique)  
- `passwordHash` – securely stored password  
- `role` – specifies whether the user is a “guest”, “host”, or “admin”

**Relationships:**
- A **User** can list multiple **Properties**.
- A **User** can make multiple **Bookings**.
- A **User** can write multiple **Reviews**.

- ## ✨ Feature Breakdown

This section outlines the core features of the Airbnb Clone project and explains how each feature contributes to creating a seamless booking experience for both guests and hosts.

---

### 👤 User Management
Users can sign up, log in, and manage their profiles securely. Authentication is handled through JWT or NextAuth, ensuring that only authorized users can access protected routes. This feature also supports different roles — such as guests and hosts — to enable specific functionality.

---

### 🏠 Property Management
Hosts can create, update, and delete property listings. Each listing includes details like price, location, amenities, and photos. This feature empowers hosts to manage their rental spaces effectively while providing guests with accurate and attractive listings to browse.

---

### 📅 Booking System
Guests can view property availability, select check-in and check-out dates, and make reservations directly through the platform. The booking system prevents overlapping reservations and provides real-time availability updates. This ensures a smooth experience for users looking to book stays.

---

### 💬 Reviews and Ratings
Guests can leave reviews and ratings after completing a stay. These reviews help build trust in the platform by allowing future guests to make informed decisions. Hosts can also respond to feedback, fostering a community of transparency and accountability.

---

### 💳 Payment Integration
The platform includes a secure payment system to process transactions between guests and hosts. Payments are tied to specific bookings, and users can view payment history. This ensures a safe and reliable checkout experience while keeping transaction records transparent.

---

### 🔍 Search and Filtering
Users can search for properties using filters such as price range, location, amenities, and availability. The search feature enhances usability by allowing guests to quickly find listings that meet their preferences and budgets.

---

### 🖥️ Admin Dashboard (Optional / Future Feature)
An administrative interface allows admins to monitor user activity, manage listings, and handle reports or disputes. This ensures the platform remains fair, secure, and well-moderated as it scales.

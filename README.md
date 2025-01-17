# Departmental Notification Management System (DNMS)

## Issue

The **Departmental Notification Management System (DNMS)** faced a significant issue with manual and disorganized management of notifications. Faculty members and administrators struggled to manage and distribute notifications regarding important departmental announcements such as schedules, meetings, and events. This led to:

- **Inefficient Communication**: No centralized platform for updating and tracking notifications.
- **Lack of Access Control**: Confusion over who could view, create, or edit notifications.
- **Manual Notification Updates**: Data had to be manually entered across different platforms, making it prone to errors.

These challenges caused delays in communication, impacting the overall workflow of the department.

## Proposed Solution

To address these issues, I developed a **centralized web-based solution** for managing departmental notifications. The primary goal was to automate and organize notification management, ensuring ease of use, security, and accessibility.

### Key Features:
1. **Role-Based Authentication**: 
   - Secure login system with user roles (admin and faculty).
   - Different roles with specific permissions to create, edit, and view notifications.

2. **Centralized Notification Dashboard**:
   - Admins and faculty can add, edit, and delete notifications.
   - Notifications are categorized, stored, and displayed in a structured format.

3. **Responsive Design**:
   - Mobile-friendly interface, accessible from any device.

4. **Database Integration**:
   - Uses **MySQL** to store user data, notifications, and roles.
   - Optimized for large datasets with quick access to notifications.

5. **Security**:
   - Passwords are hashed for security using **bcrypt**.
   - Input validation techniques prevent security vulnerabilities (SQL injection, XSS).

6. **Data Integrity**:
   - Notifications can be tracked and archived for future reference.

## Solution Implementation

### Frontend:
- Built using **HTML**, **CSS**, and **JavaScript**.
- Utilized **Bootstrap** for a responsive, mobile-friendly layout.

### Backend:
- Developed using **PHP** to handle server-side logic.
- Integrated with **MySQL** for efficient data management.

### Security:
- **Session management** and **user role checks** for authorization.
- Used **bcrypt hashing** to securely store passwords.

### Database:
- Designed a relational database schema to handle users, notifications, and departments efficiently.
- SQL queries for managing and retrieving data.

### Deployment:
- Deployed on a local server for testing with **Apache** and **MySQL**.

## Outcome

The implemented solution successfully addressed the communication gaps and disorganization within the department. The key benefits include:

- **Streamlined Notification Management**: Admins and faculty can easily manage notifications.
- **Improved Communication**: Notifications are centralized, ensuring timely updates.
- **Enhanced Security**: Role-based access control ensures secure management.
- **Responsive User Interface**: Accessible on desktop and mobile devices.
- **Scalable**: Ready to handle future growth with its database structure and application design.

This solution has greatly improved the notification management process and communication within the department.

---

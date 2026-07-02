# Library Management System (LMS)

## Project Overview
Developed as a collaborative project between the University and Tulkarm Municipality, this system was designed to address the specific needs of public library management, ensuring reliability and institutional-grade security. The system handles the entire lifecycle of library operations, including book archiving, member subscriptions, circulation/lending processes, and comprehensive staff management.

## Technical Stack
*   **Backend:** ASP.NET Core (C#)
*   **Database:** SQL Server with Entity Framework Core (EF Core)
*   **Frontend:** React
*   **Architecture:** Clean Architecture

## Key Technical Challenges & Solutions
*   **Legacy Transition:** Successfully replaced an outdated system by gathering requirements from library staff.
*   **Advanced Dynamic Authorization (RBAC + Group-based):** Instead of static, hard-coded roles, I designed a dynamic Group-Based Access Control system. The Super Admin can create custom groups and assign specific granular permissions to each, making the system highly flexible and scalable.
*   **API Security & Stability:** 
    *   Implemented **JWT (JSON Web Tokens)** for secure, stateless authentication.
    *   Integrated **Rate Limiting** on critical endpoints and the login module to prevent brute-force attacks and ensure optimal performance.

## Core Features
*   **Circulation Management:** Efficient tracking of book lending and returns.
*   **Member Subscriptions:** Automated handling of library memberships and renewals.
*   **Granular Permissions:** Fine-tuned control over staff access based on group assignments.
*   **High Performance:** Optimized database queries and API response times.

## My Role
I served as the **Backend and Database Developer** for this project, taking ownership of the system's core architecture and business logic. My key responsibilities included:

* **Database Architecture:** Architected and implemented the relational database schema, ensuring data integrity and optimized query performance.
* **API Development:** Developed secure and scalable RESTful APIs using ASP.NET Core, focusing on seamless frontend-backend communication.
* **Security & Authorization:** Engineered the dynamic, group-based access control system (RBAC) to handle complex institutional permissions with maximum flexibility.
* **System Integration:** Actively coordinated technical integration between frontend and backend components, ensuring a cohesive and high-performing system.
* This project was a joint effort. I had the pleasure of working alongside a brilliant developer, whose dedication and technical contributions were instrumental in bringing this system to life. Our teamwork, marked by constant knowledge-sharing and clean coding practices, was a key factor in the project's success.
## Live Demo
Currently, the system is deployed within the institution's private infrastructure for internal management. A public live demo is **Coming Soon**. 

In the meantime, feel free to review the architecture and implementation details outlined above.

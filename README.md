# Employee Leave Management System

## Overview

The **Employee Leave Management System** is a web-based application designed to streamline the process of leave management for employees and administrators. Employees can apply for various types of leaves (Casual Leave, Earned Leave) and track their leave balances. Administrators have full control over employee accounts, leave requests, and can generate leave-related reports.

## Key Features

- **User Registration & Activation**:
  - Employees register for the system, and their accounts are activated by administrators.
  
- **Leave Requests**:
  - Employees can apply for Casual or Earned Leave, and administrators have the authority to approve or reject requests.
  
- **Leave Balance**:
  - The system tracks and displays leave balances for each employee, ensuring no one exceeds the maximum leave days.
  
- **Reports**:
  - Admins can view leave reports, including leave histories, and employees can see a summary of their leave requests.

## Technology Stack

- **Backend Framework**: [Laravel 12](https://laravel.com/) - A PHP framework used for routing, controllers, database interaction, and business logic.
  
- **Admin Panel**: [Filament 3](https://filamentphp.com/) - A powerful admin panel to manage user data and leave requests.
  
- **Frontend**: Blade Templates (Laravel) & [Tailwind CSS](https://tailwindcss.com/) for styling.
  
- **Authentication**: Filament Authentication handles user registration, login, and access control.
  
- **Database**:
- [Sqlite](https://www.sqlite.com)
- [MySQL](https://www.mysql.com/) to store employee and leave request data.
  
- **Security**: 
  - HTTPS for secure communication.
  - Passwords are hashed using Bcrypt.
  - CSRF protection, XSS prevention, and SQL injection mitigation with Laravel's built-in methods.

## Installation Guide

### 1. Prerequisites

Ensure you have the following installed on your local machine:

- **PHP 8.3.6 or higher**
- **Composer** - PHP dependency manager
- **Node.js** (Optional for frontend asset compilation)
- **MySQL** for database management

### 2. Clone the Repository

```bash
git clone https://github.com/Abungo/leave_management_system.git
cd employee-leave-management

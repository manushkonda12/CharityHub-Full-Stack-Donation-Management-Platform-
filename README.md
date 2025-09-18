# CharityHub-Full-Stack-Donation-Management-Platform-
https://charityhub.free.nf/


# CharityHub 🤝

A full-stack donation management platform that connects donors with charitable causes, built with modern web technologies and secure donation tracking systems.

## 🌐 Live Demo

**[View Live Application](https://charityhub.free.nf/)**

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Security Features](#security-features)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

CharityHub is a comprehensive donation management web application that streamlines the process of charitable giving. The platform provides secure user authentication, real-time donation tracking, and efficient management of donation categories, making it easier for organizations to manage their charitable operations.

## ✨ Features

### Core Functionality
- **User Authentication System** - Secure login/registration with session management
- **Donation Tracking** - Real-time monitoring and recording of donations
- **Category Management** - Organized donation categories with CRUD operations
- **User Dashboard** - Personalized interface for donors and administrators
- **Secure Transactions** - Protected donation processing with data validation

### Administrative Features
- **User Management** - Admin panel for managing registered users
- **Donation Analytics** - Overview of donation patterns and statistics
- **Category Administration** - Add, edit, and remove donation categories
- **Database Management** - Secure data operations with SQL injection prevention

## 🛠️ Technologies Used

### Backend
- **PHP** - Server-side scripting and business logic
- **MySQL** - Relational database with normalized schema
- **PDO** - Database connections with prepared statements

### Frontend
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling and responsive design
- **JavaScript** - Interactive user interface and form validation

### Security
- **PDO Prepared Statements** - SQL injection prevention
- **Session Management** - Secure user authentication
- **Input Validation** - Server-side and client-side data validation

## 🚀 Installation

### Prerequisites
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Web server (Apache/Nginx)
- Modern web browser



### Database Structure
The application uses a normalized MySQL database with the following key tables:
- `users` - User account management
- `donations` - Donation records and tracking
- `categories` - Donation category classification
- `transactions` - Financial transaction logs

## 📖 Usage

### For Donors
1. **Registration/Login** - Create account or sign in
2. **Browse Categories** - Explore available donation categories
3. **Make Donations** - Securely contribute to chosen causes
4. **Track History** - View personal donation history

### For Administrators
1. **Admin Dashboard** - Access administrative controls
2. **Manage Users** - Handle user accounts and permissions
3. **Category Management** - Add/edit donation categories
4. **Monitor Donations** - Track and analyze donation patterns

## 🔒 Security Features

- **SQL Injection Prevention** - All database queries use PDO prepared statements
- **Input Sanitization** - Server-side validation and sanitization of user inputs
- **Session Security** - Secure session management with proper timeout handling
- **Password Protection** - Hashed password storage using secure algorithms
- **CSRF Protection** - Cross-Site Request Forgery prevention mechanisms

## 🚀 Deployment

The application is successfully deployed and accessible at [charityhub.free.nf](https://charityhub.free.nf/). The deployment process involved:

- Database optimization and connection troubleshooting
- Production environment configuration
- Security hardening for live deployment
- Performance optimization for web hosting

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Special recognition for the open-source community
- Inspiration from various donation management platforms

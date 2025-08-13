Real-Time Chat Application
This is a full-stack real-time chat application built with PHP, WebSockets, and vanilla JavaScript. The project implements a modern chat system with multiple advanced features.

Architecture Overview
Backend (PHP):

WebSocket Server: Uses Ratchet library for real-time WebSocket communication on port 8085
Database Layer: MySQL database with PDO for data persistence
Object-Oriented Design: Modular PHP classes for different functionalities
Frontend:

Vanilla JavaScript: No frameworks, pure JS for WebSocket communication
Responsive Design: Clean CSS styling with modern UI elements
Real-time Updates: Live message display and user presence tracking
Core Features
Real-Time Messaging

WebSocket-based instant messaging
Support for both public chat rooms and private messages
Message persistence in MySQL database
User Authentication

User registration and login system
Password hashing with bcrypt for security
Session-based authentication
Chat Rooms

Multiple chat room support
Room creation and management
Users can join different rooms
User Presence

Real-time user presence tracking
Display of online users in each room
Connection status management
Media Sharing

File upload functionality
Media storage in media/ directory
File link generation for sharing
Notifications

Browser push notifications for new messages
User presence update notifications
Permission-based notification system
Technical Stack
Backend: PHP 7+, Ratchet WebSocket library, MySQL
Frontend: HTML5, CSS3, Vanilla JavaScript

Database Schema
The application uses a MySQL database (chat_db) with tables for:

Users (authentication)
Chat rooms
Messages (with timestamps)
Media files
This is a production-ready chat application with modern real-time features, secure authentication, and a clean, responsive user interface suitable for deployment in web environments.<img width="1376" height="598" alt="Capture d’écran 2025-08-13 060121" src="https://github.com/user-attachments/assets/b4d17bd1-0ec1-47c7-8846-fb0c55dd491d" />

Database: MySQL with PDO
WebSocket: Ratchet/ReactPHP for real-time communication
Dependencies: Managed via Compose

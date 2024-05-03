
---

# PHP Chat Web Application

A simple chat web application built with PHP, MySQL, and AJAX for real-time messaging.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project is a PHP-based chat web application designed to facilitate real-time communication between users. It utilizes AJAX for seamless updates without page reloads and MySQL for database storage of chat messages. With a user-friendly interface and basic authentication system, this application provides a straightforward platform for online chatting.

## Features

- User authentication system
- Real-time messaging using AJAX
- Message encryption (optional)
- Responsive design for various devices
- Database storage for chat history

## Installation

To run this application locally, follow these steps:



1. **Import Database:**
   - Create a MySQL database and import the `database.sql` file located in the `database` folder.

2. **Configure Database Connection:**
   - Open `config.php` file located in the `includes` folder.
   - Update the database credentials (hostname, username, password, database name) accordingly.

3. **Start the Web Server:**
   - Run a local web server (e.g., Apache) with PHP support.

4. **Access the Application:**
   - Open a web browser and navigate to `http://localhost/php-chat-web`.

## Usage

1. **Register/Login:**
   - If you're a new user, register with your email and password.
   - If you're an existing user, log in with your credentials.

2. **Chatting:**
   - Once logged in, you'll be redirected to the chat interface.
   - Enter your message in the input box and press Enter or click the send button to send a message.
   - New messages will appear in real-time without refreshing the page.

3. **Logout:**
   - Click on the logout button to log out of the application.

## Contributing

Contributions are welcome! Here are some ways you can contribute to this project:

- Report bugs and suggest improvements by opening an issue.
- Fork the repository and create a pull request with your enhancements.
- Spread the word about this project and help others discover it.


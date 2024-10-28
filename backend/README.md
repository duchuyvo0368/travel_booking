# 🌐 Travel Booking Backend

Welcome to the **Travel Booking Backend**, a powerful API server designed for managing all aspects of a travel booking platform. This server supports comprehensive functionalities including tour management, user notifications, payment processing, and media handling. Built with Node.js, MongoDB, RabbitMQ, and Redis, this backend ensures smooth, reliable, and secure operations for a seamless travel booking experience.

## ✨ Features

- **Tour Management**: Create, update, and manage tour offerings with ease.
- **User Notifications**: Real-time email notifications for bookings, reminders, and updates.
- **Secure Authentication**: Employs JWT for secure, session-based user authentication.
- **Payment Gateway Integration**: Integrated VNPay (sandbox) for secure and convenient payments.
- **Media Storage**: Uses Cloudinary to manage user profile pictures and tour images.
- **Asynchronous Messaging**: RabbitMQ handles inter-service communication for efficient, decoupled processing.
## ✨ Features

- **Tour Management**: Create, update, and manage tour offerings with ease.
- **User Notifications**: Real-time email notifications for bookings, reminders, and updates.
- **Secure Authentication**: Employs JWT for secure, session-based user authentication.
- **Payment Gateway Integration**: Integrated VNPay (sandbox) for secure and convenient payments.
- **Media Storage**: Uses Cloudinary to manage user profile pictures and tour images.
- **Asynchronous Messaging**: RabbitMQ handles inter-service communication for efficient, decoupled processing.

## 🚀 Technology Stack

### Backend Technologies
- **Node.js**: A JavaScript runtime built on Chrome's V8 engine, allowing for fast and scalable network applications. It's designed to build server-side applications and APIs.
- **Express**: A minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications, allowing for easy routing and middleware integration.
- **MongoDB**: A NoSQL database that stores data in flexible, JSON-like documents. This allows for dynamic schema designs and is perfect for handling complex data structures in travel bookings.
- **RabbitMQ**: An open-source message broker that facilitates the communication between services in a decoupled manner, enabling better scalability and reliability of messaging.
- **Redis**: An in-memory data structure store used as a database, cache, and message broker. It provides high performance for data retrieval and is utilized for caching and session management in this application.
- **Cloudinary**: A cloud-based service for managing images and videos, allowing easy storage, manipulation, and delivery of media assets.

### Libraries and Frameworks
- **JWT (JSON Web Tokens)**: Used for secure user authentication and authorization, allowing for stateless sessions and preventing unauthorized access to protected routes.
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js, providing a straightforward way to model and interact with MongoDB data.
- **Nodemailer**: A module for Node.js to send emails easily, utilized in the notification service for sending booking confirmations and reminders.
- **dotenv**: A zero-dependency module that loads environment variables from a `.env` file into `process.env`, enabling configuration management for different environments.

Create .env file in notification service

```bash
NODE_ENV=development
PORT=4002
CLIENT_URL=
RABBITMQ_ENDPOINT=amqps://hxcogcza:cU1DuN2iHmYndFue4odwleYX4g9LRfz-@octopus.rmq3.cloudamqp.com/hxcogcza
HOST_MAIL=sandbox.smtp.mailtrap.io
PORT_MAIL=***
USER_MAIL=***
USER_MAIL_PASS=***
SENDER_MAIL=***@gmail.com
```

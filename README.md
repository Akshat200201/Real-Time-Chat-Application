# Real-Time Chat Application

  This is a chat application project that allows users to communicate with each other in real-time. It is built using the Spring Boot framework for the backend, SockJS for WebSocket communication, and React for the frontend. The project utilizes Maven as the build tool for the backend.
## Features
-  __User Authentication__: Users are required to log in with a username before they can access the chat application.
- __Real-time Chat__: Once logged in, users are directed to the chat page where they can send messages in the chatroom.
- __User Presence__: Users are notified when new users join the chatroom, allowing them to be aware of other participants.
- __Private Messages__: Users have the ability to send private messages to specific individuals.
- __Multimedia Transfer__: The application supports the transfer of multimedia files, such as photos and videos.
- __Logout__: Users can log out from the application, and their username will be removed from the user list displayed to other participants.

## Tech Stack
The application incorporates the following technologies:

- __Spring Boot__: A Java-based framework used for building the backend server and handling business logic.
- __SockJS__: A WebSocket emulation library that enables real-time communication between the server and clients.
- __React__: A JavaScript library used for building the user interface and handling frontend functionality.

## Setup Instructions
To run the chat application locally, follow these steps:

1. __Navigate to the project directory__: ```cd chatroom-backend```
2. __Set up the backend server__:
   - Install the necessary dependencies: ```mvn clean install```
   - Start the Spring Boot server: ```mvn spring-boot:run```
3. __Set up the frontend__:
   - Install the necessary dependencies: ```cd chatroom-ui``` && ```npm install```
   - Start the React development server: ```npm run dev```
4. __Open your web browser__ and visit ```http://localhost:5173``` to access the chat application.

## Screenshots
Here are some screenshots of the chat application:

1. Login Page
![](https://github.com/Akshat200201/Springboot-chatapp-master/blob/main/img/login-vid.gif)

2. Chat Page
- Chatroom ![](https://github.com/Akshat200201/Springboot-chatapp-master/blob/main/img/Chat-2.png)
- Private Text ![](https://github.com/Akshat200201/Springboot-chatapp-master/blob/main/img/Chat-1.png)


## Project Database Configuration Note

**Important: Local Database Setup Required**

This project relies on a local database for certain functionalities. However, please note that the local database may not be readily available when the project is run on local machines due to monetary constraints. To ensure the smooth functioning of the project and enjoy its full potential, it is crucial to configure the local database using the schema defined in the backend files else some chatting functionalities may not work as expected.

**Note:**
   Failure to configure the local database as instructed may result in impaired functionality of certain chat features. To fully experience the capabilities of this project, it is essential to have a functional local database.

We understand the limitations posed by the use of a local database due to some constraints. We appreciate your understanding and hope that these instructions facilitate a seamless setup for your local development environment.


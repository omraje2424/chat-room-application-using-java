# chat-room-application-using-java
# chat-room-app-using-java
AUTHOR OMRAJE SHINDE 
Here’s a sample `README.md` file for your Java-based Chat Room Application, highlighting the technologies you've used, including AWT, Swing, event handling, database connection, and networking concepts:

---

# Chat Room Application

### Description
The **Chat Room Application** is a Java-based project that allows users to communicate with each other in real-time through a user-friendly graphical interface. The project is built using **AWT (Abstract Window Toolkit)** and **Swing** for the GUI, **event handling** for user interactions, **JDBC** for database connections, and **socket programming** for networking functionality. The application supports real-time messaging and user registration, making it an efficient platform for communication.

---

## Features
- **Real-time Messaging**: Users can send and receive messages in real-time without refreshing.

- **User Authentication**: Only registered users can enter the chat room.
- **Multiple Client Support**: Supports communication between multiple users on the same network.

---

## Technologies Used
- **Java AWT & Swing**: For creating the graphical user interface.
- **Event Handling**: To manage user interactions such as button clicks and message sending.
- **Networking (Socket Programming)**: Enables communication between the client and server.
- **JDBC (Java Database Connectivity)**: Manages the connection between the application and the MySQL database.
- **MySQL Database**: Stores user information and chat history.
  
---

## Installation and Setup

### Prerequisites
- Java JDK 8 or higher
- MySQL Database
- IDE such as NetBeans or IntelliJ IDEA
- MySQL JDBC Driver

### Steps to Run the Application

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/omraje2424/ChatRoomApp.git
    ```

2. **Configure the Database**:
   - Install MySQL and create a database named `chatappdb`.
   - Create the required tables for storing user data and chat messages:
     ```sql
     CREATE DATABASE chatappdb;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) NOT NULL,
    registration_time TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

     ```

3. **Update Database Credentials**:
   - Open the `ChatRoomApp` project and update the MySQL database connection settings in the JDBC code:
     ```java
     String url = "jdbc:mysql://localhost:3306/chatapp";
     String username = "root";
     String password = "yourpassword";
     ```

4. **Run the Application**:
   - Compile and run the server-side and client-side applications in your preferred IDE.

---

## Usage

- **Login/Sign-Up**: not requreied beacause it just the virtual chat window any one can access
- **Start Chatting**: Once logged in, users can start chatting with others. Select the chat partner's name from the database to initiate the chat.
- this is just a online chat room where multiple people are just come togher and chat 
- main useges of this project is just create a app where all can chat same time just like whatsapp group
---

## Screenshots
(Include screenshots of the application’s GUI here.)
![image](https://github.com/user-attachments/assets/418693b7-ceac-49c2-86f7-80cb6ab7862f)
![image](https://github.com/user-attachments/assets/6a4eea77-7686-450d-8503-d1829a2d53f9)
![image](https://github.com/user-attachments/assets/c54722f0-4041-4c0c-ac2c-32540df9ec89)
![image](https://github.com/user-attachments/assets/7187fdba-399d-4889-8bca-35bd910bd378)
![image](https://github.com/user-attachments/assets/3dbbbddb-d8be-47d2-9032-8bd7657b7e0f)







---

## Contribution

Feel free to contribute to this project by forking the repository and creating pull requests. Issues and improvements are always welcome.

---



---

## Contact
For further inquiries or contributions, please contact:

- Email: omrajeshinde2424@gmail.com

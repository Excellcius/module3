# Overview
As a software engineer, my primary goal is to continue learning and growing in my field. Learning is an ongoing journey, and in the rapidly evolving world of technology, it's essential to stay up to date with the latest trends, tools, and techniques. My aim is to expand my knowledge and skills continuously, keep up with emerging technologies, and contribute to meaningful projects.

One of the projects I've been working on is a cloud-based To-Do List application integrated with a Firestore database, which is a part of Google Firebase. This application is designed to help users efficiently manage their tasks, providing features like creating new tasks, marking completed items, updating task details, and removing unnecessary entries. To ensure data privacy and secure access, the application includes user authentication, requiring users to log in to access their tasks.

This project allows me to gain practical experience with cloud-based application development, particularly with Firestore and Firebase. It involves understanding how to manage user data securely in the cloud and integrating authentication mechanisms. By working on this project, I aim to enhance my skills in cloud development, databases, and user authentication.

[Software Demo Video](https://www.youtube.com/watch?v=urnSyQPUmmc)

# Cloud Database

The cloud database I'm using for the To-Do List application is Firestore, which is a part of Google Firebase. Firestore is a NoSQL document database that is well-suited for real-time applications and cloud-based projects. It offers seamless integration with Firebase services, including user authentication, making it an excellent choice for applications that require secure data storage and user management.

In Firestore, data is organized into collections. For this application, I have a collection called "tasks." Each collection contains a set of related documents. In this case, the "tasks" collection stores the individual to-do list tasks.

Documents: Within the "tasks" collection, each to-do list task is represented as a document. Documents are individual records, and they are uniquely identified by an auto-generated ID. The document structure includes two main fields:

    user_id: This field stores the user ID of the person who created the task. It is used for associating tasks with specific users, ensuring that each user has their private set of tasks.

    task: This field contains the description of the task entered by the user.

# Development Environment
 I primarily used Python for developing the application. Python is known for its simplicity and versatility, making it suitable for a wide range of application development tasks. I leveraged Google Firebase for various aspects of the application, including Firestore for the cloud database, Firebase Authentication for user management, and Firebase Admin SDK for server-side operations. To interact with Firebase services from the server-side (backend) of the application, I used the firebase-admin library. This library allows Python applications to work with Firebase services programmatically.
# Useful Websites

{Make a list of websites that you found helpful in this project}

- [Firebase Website](https://firebase.google.com/?authuser=0)
- [Firebase Console](https://firebase.google.com/docs/firestore)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}

- Fix the user warning that vscode gives me.
- Implement real-time synchronization with the Firestore database, so updates are immediately reflected across all user devices.
- Develop a mobile app version to provide a seamless mobile experience.
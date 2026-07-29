[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_ICeFLKz)
# DGL 104 - Task Management System (TMS)
# Task Management System (TMS)

## Project Description
The Task Management System (TMS) is an Android application developed in Kotlin using Firebase Authentication and Cloud Firestore. The application allows users to create, assign, edit, delete, and track tasks.

## Introduction
This application was developed for the DGL104 Application Development course. The objective was to build a scalable task management system while implementing software design patterns, debugging techniques, Firebase integration, and a basic CI/CD pipeline.


## Tech Stack
- Kotlin
- Android Studio
- Firebase Authentication
- Cloud Firestore
- RecyclerView
- GitHub
- GitHub Actions

## Unique Features
- User Registration
- User Login
- Firebase Authentication
- Create Tasks
- Edit Tasks
- Delete Tasks
- Assign Tasks to Users
- Set Priority Levels
- Set Due Dates
- Track Task Status
- Firebase Cloud Firestore Database
- Observer Notifications
- Error Logging
- GitHub Actions CI/CD

## Design Patterns Used

### Singleton Pattern
FirebaseSingleton provides a single Firestore database instance that is shared throughout the application.

### Factory Pattern
UserFactory creates different user roles including:

- Admin
- Manager
- Developer
- Tester

### Observer Pattern
The application uses the Observer pattern through:
- TaskSubject
- TaskObserver
- TaskLogger

Whenever a task is created, updated, or deleted, registered observers are notified.

### Strategy Pattern
PriorityStrategy calculates task priority using interchangeable prioritization strategies.

## Installation Guidelines
1. Download the ZIP file.
2. Extract the file's contents
3. Open Android Studio.
4. Click File -> Open
5. Find the project and open the project using settings.gradle.kts
6. Connect the project to Firebase.
7. Run the application.

## Summary of the Project
Building this app gave me a better understanding on how the inner workings of an app run and work together. Moving on to the app, the app allows users to create an account, log in, and manage their tasks by creating, editing, assigning, updating, and deleting them. Each task includes a priority level, due date, assigned user, and status so users can keep track of their work more effectively.
One of the biggest parts of this project was learning how to use Firebase Authentication and Cloud Firestore to securely store user accounts and task information. I also implemented several software design patterns, including Singleton, Factory, Observer, and Strategy, to make the code more organized, reusable, and easier to maintain.
During development, I ran into several challenges, especially when setting up Firebase and debugging issues with task updates and deletions. Working through those problems helped me become more comfortable using Logcat, debugging tools, and testing different solutions until everything worked correctly. (Although I still need improving)
Overall, this project improved my understanding of Android development, Firebase integration, software design patterns, and good coding practices. It also showed me the importance of writing clean, maintainable code and using version control and continuous integration to support the development process. I just hope I don't have too much redundant code still in it.

## Contrubutions
- Implemented Firebase Authentication
- Integrated Cloud Firestore database
- Developed full CRUD functionality
- Added task assignment
- Implemented due dates and priority levels
- Implemented Singleton, Factory, Observer, and Strategy patterns
- Added logging for debugging
- Configured GitHub Actions for CI/CD

## References
Android Developers - Android developer documentation. https://developer.android.com/

Firebase - Firebase documentation. https://firebase.google.com/docs

Firebase - Cloud Firestore documentation. https://firebase.google.com/docs/firestore

Firebase - Firebase Authentication documentation. https://firebase.google.com/docs/auth

JetBrains - Kotlin documentation. https://kotlinlang.org/docs/home.html

GitHub - GitHub Actions documentation. https://docs.github.com/actions

Material Design - Material Design 3. https://m3.material.io/

Wikipedia - Can't remember exactly what I searched up, but it was mainly on understanding what a certain object/class was.

How to Build a Beautiful Task Manager App - Android Kotlin MVVM Room Database Tutorial - Used as a basic guideline/reference on what the app was supposed to be. https://www.youtube.com/watch?v=UU3FzCBKhEw&t=3300s

ChatGPT - used to help with debugging and implementation of the app. (Note I am not really that good at coding yet, so I get lost easily)

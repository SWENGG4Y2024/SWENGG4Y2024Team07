# Online Learning Management System (LMS) Architecture
 
## System Context Diagram
 
![System Context Diagram](Architecture/context.png)
 
The System Context Diagram provides an overview of the LMS and its interactions with external users and systems. The main actors interacting with the LMS are students, instructors, and administrators.
 
## Container Diagram
 
![Container Diagram](Architecture/container.png)
 
The Container Diagram shows the high-level containers within the LMS. The main containers are:
 
- **Web Application**: The front-end interface for users.
- **API Gateway**: Handles API requests and routes them to the appropriate services.
- **Course Management Service**: Manages course creation, updates, and deletions.
- **User Management Service**: Manages user accounts and permissions.
- **Quiz and Assignment Service**: Manages quizzes and assignments.
- **Database**: Stores all the data related to courses, users, and quizzes.
 
## Summary
 
This document provides a high-level overview of the Online Learning Management System (LMS) architecture using the C4 model. The diagrams included illustrate the context and container views of the system, highlighting its major components and interactions.

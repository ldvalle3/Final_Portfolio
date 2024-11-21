# Mindfull Sequencing - Backend Module - 
[Backend module link](https://github.com/ldvalle3/YogaSequencingApp1/tree/backend_module)

## High Level Overview of the Project Purpose  
### Users
The primary users of this application are yoga instructors who seek an efficient and intuitive tool to create, organize, and manage custom yoga sequences for their classes.

### Job It Performs for Users
The application allows yoga instructors to:
  - Design personalized yoga sequences.
  - Save and reuse sequences for future classes.
  - Easily update or modify sequences as needed.
  - Enhance their workflow by having a structured digital resource.
### Inspiration
The inspiration for this project came from observing the challenges yoga instructors face in planning their sessions. Many rely on paper or generic tools that aren't tailored to yoga-specific needs. I aimed to create a user-friendly platform that bridges this gap by offering a solution specifically designed for yoga instructors.

### Most Important Features
  - Sequence Builder: A drag-and-drop interface to create yoga flows.
  - User Authentication: OAuth integration for secure sign-ins.
  - Session Persistence: JWT web tokens for seamless user experiences across sessions.
  - Error Handling: Comprehensive validation and error messages to guide users.
  - Task Management: Tools to categorize and manage multiple sequences.

<img width="831" alt="Screenshot 2024-03-19 182910" src="https://github.com/user-attachments/assets/a1ecee39-dc8c-4c65-b8b1-c9b69fff99e7">

    
## STAR Interview Framework
### (Situation)
Yoga instructors often face difficulties in organizing their class sequences efficiently. To address this issue, I created a yoga sequencing application, empowering instructors to craft customized sequences while ensuring security and user-friendly functionality.

### (Task)
I planned the application with a modular structure, designing a backend to handle authentication, validation, and data management and a frontend to enable intuitive sequence creation. I prioritized a clean and scalable design with clear user flows and robust functionality.

### (Action)
  - Integrated OAuth for secure third-party login.
  - Implemented JWT web tokens to maintain session persistence.
  -  Designed APIs with validation/error handling for smooth operation.
  - Added task management to organize sequences effectively.

### (Result)
The final application provides yoga instructors with a tailored tool to efficiently create and manage sequences. Its secure login, seamless session handling, and error-free operation make it a reliable resource for their needs.

## Technologies Used
### Programming Language
  - JavaScript
  - Python
### Backend Technologies
  - Node.js
  - Flask
  - Express.js
  - JWT
  - OAuth
  - jinja synax
### Frontend Technologies
  - HTML5, CSS3
### Database
  -  SQLalchemy
## Competencies

<img width="355" alt="Screenshot 2024-03-19 183037" src="https://github.com/user-attachments/assets/5ee7e0de-e9b8-4a5b-9e11-478c8ef81847">


### JF 3.7: Can Implement Authentication to an API
#### Implementation in the Yoga Sequencing Application:
Authentication was a critical component of the backend module to ensure that only authorized users could access the application. This was achieved using OAuth and JWT (JSON Web Tokens).
  - OAuth: I implemented OAuth to allow users to sign in using a secure, third-party authentication provider. This simplified user access while keeping their credentials secure.
    - Example: Integration with Google or Facebook OAuth APIs to streamline login processes.
  - JWT Authentication: After a user logs in, the backend generates a JWT, which is sent to the client. This token is required for subsequent requests to access protected resources.
    - Example: Once a yoga instructor logs in, their token is used to authenticate API requests for managing sequences or retrieving user-specific data.
    - 
#### Steps Demonstrated:
  - Set up OAuth to authenticate users via external providers.
  - Configured the API to issue and validate JWTs for session management.
  - Ensured token expiry and refresh mechanisms were in place to enhance security.

### JF 2.5: Can Implement Authorization to an API
#### Implementation in the Yoga Sequencing Application:
Authorization ensures that authenticated users only access resources or perform actions they are permitted to. This was implemented through role-based and resource-based access controls.
  - Role-Based Access Control (RBAC): Users were assigned roles (e.g., instructor, admin), and permissions were granted based on these roles.
    - Example: Admins could manage all user accounts, while instructors could only access and modify their own sequences.
  - Middleware for Route Protection: Implemented middleware to verify the user's role and permissions before granting access to specific API endpoints.
    - Example: The /admin/dashboard route checks if the user's role is "admin" before granting access. Similarly, the /sequence/edit endpoint ensures the user owns the sequence they're modifying.
#### Steps Demonstrated:
  - Created middleware to validate JWTs and extract user roles.
  - Applied role-based access rules to critical API routes.
  -  Ensured resource-specific validation (e.g., verifying ownership of sequences).

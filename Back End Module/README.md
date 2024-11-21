###Mindfull Sequencing - backend module - 
[Backend module link](https://github.com/ldvalle3/YogaSequencingApp1/tree/backend_module)

##Overview 
Users
The primary users of this application are yoga instructors who seek an efficient and intuitive tool to create, organize, and manage custom yoga sequences for their classes.

Job It Performs for Users
The application allows yoga instructors to:

Design personalized yoga sequences.
Save and reuse sequences for future classes.
Easily update or modify sequences as needed.
Enhance their workflow by having a structured digital resource.
Inspiration
The inspiration for this project came from observing the challenges yoga instructors face in planning their sessions. Many rely on paper or generic tools that aren't tailored to yoga-specific needs. I aimed to create a user-friendly platform that bridges this gap by offering a solution specifically designed for yoga instructors.

Most Important Features
Sequence Builder: A drag-and-drop interface to create yoga flows.
User Authentication: OAuth integration for secure sign-ins.
Session Persistence: JWT web tokens for seamless user experiences across sessions.
Error Handling: Comprehensive validation and error messages to guide users.
Task Management: Tools to categorize and manage multiple sequences.
STAR Interview Framework
(Situation)
Yoga instructors often face difficulties in organizing their class sequences efficiently. To address this issue, I created a yoga sequencing application, empowering instructors to craft customized sequences while ensuring security and user-friendly functionality.

(Task)
I planned the application with a modular structure, designing a backend to handle authentication, validation, and data management and a frontend to enable intuitive sequence creation. I prioritized a clean and scalable design with clear user flows and robust functionality.

(Action)
For the backend:

Integrated OAuth for secure third-party login.
Implemented JWT web tokens to maintain session persistence.
Designed APIs with validation/error handling for smooth operation.
Added task management to organize sequences effectively.
For the frontend:

Built an interactive sequence builder using JavaScript.
Ensured a responsive design with intuitive navigation for the end user.
(Result)
The final application provides yoga instructors with a tailored tool to efficiently create and manage sequences. Its secure login, seamless session handling, and error-free operation make it a reliable resource for their needs.

Technologies Used
Programming Language
JavaScript (ES6+)
Backend Technologies
Node.js: v14.x
Express.js: v4.x
JWT: v8.x
OAuth 2.0: via Passport.js
Frontend Technologies
HTML5, CSS3
Vanilla JavaScript
Database
MongoDB: v5.x
Dependencies
bcrypt.js: v5.x (for password hashing)
Mongoose: v6.x (for database modeling)
dotenv: v16.x (for environment variable management)
Deployment Tools
Heroku: For deployment of the backend and frontend.
GitHub Actions: For CI/CD workflows.

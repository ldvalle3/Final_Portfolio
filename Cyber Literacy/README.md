# Mindfull Sequencing - Cyber Literacy - 
[Cyber Literacy Link](https://github.com/ldvalle3/YogaSequencingApp1/tree/deployment-module)

## High LEvel Overview of the Project Purpose
### Users
The users are primarily yoga instructors who interact with the application, as well as administrators managing user data and ensuring the overall security of the app.

### Job It Performs for Users
The cybersecurity measures protect users' data, prevent unauthorized access, and maintain the integrity of the application. These measures ensure:
    - Data Security: Safeguards sensitive user data, including passwords and personal information.
    - Account Integrity: Protects user accounts by enforcing strong security practices like password complexity.
    - Activity Tracking: Monitors and logs user activity to detect and prevent any suspicious behavior.
### Inspiration
The inspiration for elevating the security of the application stemmed from the need to protect user data and maintain trust. Given that the app handles personal information, secure authentication and proactive monitoring were crucial to mitigate potential security risks.

### Most Important Features
  - Input Validation and Sanitization: Prevents harmful inputs from being executed or processed by the system.
  - Password Security: Enforces a specific password complexity requirement to ensure users' accounts are secure.
  - Activity Logging: Tracks and records user actions and security events, enabling better detection of any suspicious activity.
## STAR Interview Framework
### (Situation)
The yoga sequencing application needed to handle user data securely while ensuring that both user information and the integrity of the app were protected from common security vulnerabilities.

### (Task)
My task was to implement various security features to safeguard the application, including proper input validation, password security, and activity logging to prevent unauthorized access and ensure accountability.

### (Action)
  - Implemented input validation and sanitization to ensure that only safe, expected data is processed.
  - Added password complexity rules (e.g., a minimum number of characters, use of special characters, etc.) to ensure strong user authentication.
  - Configured a logging mechanism to capture and monitor user activities and potential security events. This log includes access logs, error logs, and any suspicious activities, providing traceability in case of a security breach.
### (Result)
These security measures significantly improved the overall integrity of the application, making it more resilient against common security risks like SQL injection, cross-site scripting (XSS), and unauthorized access. The application now has stronger protection for user data and a more secure authentication process.

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
### Security
  - Flask-limiter library
  - rotating file handler
    
## Competencies
### JF 5.3: Understands how to conduct a range of test types, such as Integration, System, User Acceptance, Non-Functional, Performance and Security testing.
Execution in the Yoga Sequencing Application:
To ensure the application was secure and functional, I applied various testing methodologies:
  - Integration Testing:
    - Verified that different components (e.g., user authentication, sequence management, and pose library) worked together seamlessly.
    - Example: Tested the flow of a user logging in, creating a sequence, and saving it to the database to ensure API endpoints integrated correctly with the frontend.
  - System Testing:
    - Conducted end-to-end testing of the entire application to validate it met the requirements and functioned correctly in a production-like environment.
    - Example: Ensured that instructors could perform all actions—login, create, edit, and save sequences—without encountering errors.
  - User Acceptance Testing (UAT):
    - Worked with potential users (yoga instructors) to evaluate the application and gather feedback on usability and functionality.
    - Example: Iterated on the drag-and-drop interface based on user feedback to improve its intuitiveness.
  - Non-Functional Testing:
    - Focused on the system’s reliability, performance, and scalability.
    - Example: Ensured the application performed well under load by simulating multiple users accessing the pose library simultaneously.
  - Performance Testing:
    - Measured the application’s response times and resource utilization under normal and peak conditions.
    - Example: Optimized backend queries to handle a large database of poses efficiently.
  - Security Testing:
    - Identified and resolved vulnerabilities in user input handling, password storage, and API endpoints.
    - Example: Conducted SQL injection tests to verify that the backend was resilient to malicious queries, and tested password complexity requirements for robustness.


### JF 5.6: Understands how to follow testing frameworks and methodologies
Execution in the Cyber Literacy Module:
Following established testing frameworks and methodologies ensured a structured approach to testing and maintained high-quality standards throughout the application:
  - Adherence to Testing Frameworks:
    - Used industry-standard tools like Jest and Postman for different types of testing.
    - Example: Jest was used for unit and integration tests, while Postman was employed to validate API endpoints and simulate user workflows.
  - Test-Driven Development (TDD):
    - Followed the TDD methodology, writing tests before implementing features to ensure the code met the expected requirements.
    - Example: Developed test cases for input validation (e.g., password complexity and sanitized text fields) before writing the actual implementation.
  - OWASP Guidelines:
    - Followed the OWASP (Open Web Application Security Project) guidelines for security testing to ensure robust protection against common vulnerabilities.
    -  Example: Verified the implementation of input sanitization and cross-site scripting (XSS) prevention techniques.
  -  Systematic Test Plan:
    - Created a test plan outlining the scope, objectives, resources, and schedule for testing activities.
    - Example: Documented which components needed security testing, how they would be tested, and what tools would be used.
  - Automation in Testing:
    - Automated repetitive tests, such as API integration and performance tests, to increase efficiency.
    - Example: Created scripts to run automated tests on CI/CD pipelines, ensuring consistent test coverage for every new code deployment.

#Mindfull Sequencing - Cyber Literacy - 
[Link to Cyber Literacy branch](https://github.com/ldvalle3/YogaSequencingApp1/tree/deployment-module)

Users
The users are primarily yoga instructors who interact with the application, as well as administrators managing user data and ensuring the overall security of the app.

Job It Performs for Users
The cybersecurity measures protect users' data, prevent unauthorized access, and maintain the integrity of the application. These measures ensure:

Data Security: Safeguards sensitive user data, including passwords and personal information.
Account Integrity: Protects user accounts by enforcing strong security practices like password complexity.
Activity Tracking: Monitors and logs user activity to detect and prevent any suspicious behavior.
Inspiration
The inspiration for elevating the security of the application stemmed from the need to protect user data and maintain trust. Given that the app handles personal information, secure authentication and proactive monitoring were crucial to mitigate potential security risks.

Most Important Features
Input Validation and Sanitization: Prevents harmful inputs from being executed or processed by the system.
Password Security: Enforces a specific password complexity requirement to ensure users' accounts are secure.
Activity Logging: Tracks and records user actions and security events, enabling better detection of any suspicious activity.
STAR Interview Framework
(Situation)
The yoga sequencing application needed to handle user data securely while ensuring that both user information and the integrity of the app were protected from common security vulnerabilities.

(Task)
My task was to implement various security features to safeguard the application, including proper input validation, password security, and activity logging to prevent unauthorized access and ensure accountability.

(Action)
Implemented input validation and sanitization to ensure that only safe, expected data is processed.
Added password complexity rules (e.g., a minimum number of characters, use of special characters, etc.) to ensure strong user authentication.
Configured a logging mechanism to capture and monitor user activities and potential security events. This log includes access logs, error logs, and any suspicious activities, providing traceability in case of a security breach.
(Result)
These security measures significantly improved the overall integrity of the application, making it more resilient against common security risks like SQL injection, cross-site scripting (XSS), and unauthorized access. The application now has stronger protection for user data and a more secure authentication process.

Technologies Used
Security Measures
Express Validator: v6.x (for input validation and sanitization)
bcrypt: v5.x (for password hashing and security)
Helmet.js: v4.x (for setting HTTP headers to secure the application)
Logging
Winston: v3.x (for logging user activities and security events)
Morgan: v1.x (for HTTP request logging)
Other Tools
CORS: (Cross-Origin Resource Sharing) configuration to prevent unauthorized domains from accessing the app.
JWT (JSON Web Tokens): for secure session management and authentication.

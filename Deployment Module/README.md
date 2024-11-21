# Mindful Sequencing - Deployment Module - 
[Link to deployment branch](https://github.com/ldvalle3/YogaSequencingApp1/tree/deployment-module)

## High-Level Overview of the Deployment Module Purpose
### Users
The users for the deployment module are the development team and operations responsible for ensuring the application is built, tested, and deployed efficiently with minimal downtime or manual intervention.

### Job It Performs for Users
The deployment module automates and streamlines the process of building, testing, and deploying the application, making it:
  - Easier to maintain consistent deployment practices.
  - More reliable with automated test coverage ensuring quality.
  - Faster by removing manual processes through continuous integration and deployment (CI/CD).
### Inspiration
The inspiration for implementing the deployment module was to ensure that updates to the yoga sequencing application could be released quickly, reliably, and with confidence. With continuous integration and automated testing, I wanted to eliminate errors during deployment and reduce the manual overhead of managing builds.

![Screenshot 2024-08-15 000437](https://github.com/user-attachments/assets/b5c49c1d-4c7e-4b9d-b343-c8f389a8f38a)

### Most Important Features
  - Automated Builds: Ensures the latest code is compiled and built automatically upon pushing changes.
  - Testing Processes: Run tests automatically as part of the CI pipeline, ensuring quality control.
  - Deployment Automations: Automatically deploys the application after passing tests.
  - Test Coverage: Includes code coverage checks to ensure tests are comprehensive.
  - Versioning & Tagging: Ensures that releases are tagged and versioned properly, improving release management.
## STAR Interview Framework
### (Situation)
Managing application deployments manually can lead to errors, delays, and inconsistent deployments. To address this, I built an automated deployment module for the yoga sequencing application, ensuring builds, tests, and deployments are handled seamlessly.

### (Task)
My task was to integrate automated processes into the application's deployment cycle. This involved setting up continuous integration (CI) and continuous deployment (CD) workflows, automating the testing, versioning, and deployment process to improve efficiency.

### (Action)
  - Set up automated builds that trigger every time code is pushed to the repository.
  - Integrated automated testing processes to ensure all code changes are validated with unit tests and integration tests.
  - Configured deployment automation so that once the tests pass, the application is deployed automatically.
  - Used versioning and tagging to label releases and ensure proper management of application versions.
### (Result)
The deployment module has significantly streamlined the release process for the yoga sequencing application. Now, each deployment is automatic, tested, and versioned, reducing the risk of errors and manual mistakes, while also speeding up the release cycle.

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
### Deployment tools
  - Jest
  - AWS
  - github actions
  - Docker containerization

![Screenshot 2024-08-14 235748](https://github.com/user-attachments/assets/e87e103e-acc6-4e76-b8e7-e3e5025564f8)

## Competencies
### JF 6.6: Shows initiative for solving problems within their own remit, being resourceful when faced with a problem to solve
#### Execution in the Deployment Process:
When challenges arose, I demonstrated initiative and resourcefulness by:
  - Researching Deployment Tools:
    - Explored and compared various deployment tools to identify the best fit for the application’s needs.
    - Example: Selected GitHub Actions for its integration with the repository and ability to handle CI/CD tasks effectively.
  - Debugging Deployment Issues:
    - Faced issues such as build failures and misconfigurations during initial deployment attempts.
    - Example: Researched error logs and consulted documentation to troubleshoot and resolve problems, such as incorrect permissions for the AWS EC2 instance or outdated dependencies.
  - Optimizing the Pipeline:
    - Identified inefficiencies in the pipeline, such as long build times, and optimized them by caching dependencies and parallelizing tasks.
    - Example: Reduced build time by implementing dependency caching in the CI pipeline, saving significant time during repeated builds.
Proactively Monitoring and Improving:
    - Set up monitoring tools to track deployment performance and proactively addressed issues.
    - Example: Used CloudWatch to monitor server health and configured alerts for potential problems, ensuring prompt responses to issues.

### JS 4.3: Is able to build, manage and deploy code into the relevant environment
#### Execution in the Yoga Sequencing Application:
Managing the deployment process required setting up a seamless and reliable pipeline to move the application from development to production. This competency was demonstrated by:
  - Automated Builds and Continuous Integration (CI):
    - Configured GitHub Actions to automate builds whenever new code was pushed to the repository or a pull request was created.
    - Example: The CI workflow ran tests, built the application, and flagged issues before code could be merged.
  - Continuous Deployment (CD):
    - Deployed the application automatically to a staging environment for review, and to production after passing all tests and reviews.
    - Example: Used AWS services (e.g., EC2) with a deployment script triggered by GitHub Actions to streamline the deployment process.
  - Versioning and Tagging:
    - Implemented a versioning system to track changes and maintain clear documentation for releases.
    - Example: Used semantic versioning (v1.0.0, v1.1.0) and Git tags to manage and identify stable builds.
  - Environment-Specific Configurations:
    - Set up environment variables for production and development environments to ensure the application behaved correctly in different contexts.
    - Example: Used .env files for environment-specific API keys and database configurations, preventing sensitive data exposure.


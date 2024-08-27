# Ansh-TarunCloudSecurityProject

Cloud Security project for COSC 55 24X

## **Introduction**

This project addresses the critical need to protect web applications from DDoS attacks and other common exploits. 
Our solution uses AWS Lambda to block malicious IP addresses, ensuring robust security for any web application.

Key Features include:

**IP Address Blocking**: The Lambda function adds offending IP addresses to an AWS WAF IP Set, blocking them from further access.

**Abnormal Traffic Detection**: The system detects unusual traffic patterns, such as a high request rate from specific IP addresses, using Siege flood and CloudWatch Logs.

**Effective Monitoring**: CloudWatch Logs provide detailed monitoring of traffic, helping identify potential threats based on request rates and other metrics.

This repository provides all necessary resources and instructions to deploy this solution, enhancing an application's defense.

## **Installation**

To install this project, follow these steps:

1. Clone the repository: **`git clone https://github.com/user/Ansh-TarunCloudSecurityProject.git`**
2. Navigate to the project directory: **`cd Ansh-TarunCloudSecurityProject`**
3. Install dependencies: **`npm install`**
4. Build the project: **`npm run build`**
5. Start the project: **`npm start`**

## **Usage**

To use this project, follow these steps:

1. Open the project in your favorite code editor.
2. Modify the source code to fit your needs.
3. Build the project: **`npm run build`**
4. Start the project: **`npm start`**
5. Use the project as desired.

## **Contributing**

If you'd like to contribute to this project, here are some guidelines:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes.
4. Write tests to cover your changes.
5. Run the tests to ensure they pass.
6. Commit your changes.
7. Push your changes to your forked repository.
8. Submit a pull request.

## **Authors and Acknowledgment**

Project Title was created by Tarun Kumaran & Ansh Motiani, two rising juniors at Dartmouth College.

Thank you to Professor Goldstein and the TAs for their invaluable guidance, insight, and knowledge in aiding our learning this term & completion of this project.

## **Contact**

If you have any questions or comments about our Cloud Security Solution, please contact the authors at tarun.i.kumaran.26@dartmouth.edu or ansh.motiani.26@dartmouth.edu.

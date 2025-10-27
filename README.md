# CS305 #

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**
Artemis Financial is a client of my company Global Rain. Artemis Financial essentially wants file verification step to added its web application to ensure secure communications. When the web application is used to transfer data, the company needed a data verification step in the form of a checksum. 


**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**
I did well in identifying and addressing potential vulnerabilities related to data transmission and integrity verification. I ensured that communication occurred over HTTPS and that all sensitive data handled by the application was verified using secure cryptographic methods.

**Which part of the vulnerability assessment was challenging or helpful to you?**
One section that proved difficult was getting the vulnerable dependencies list (From the OWASP dependency scanner) to show 0 vulnerable depencies. It seemed that the only way to do this was to update all highlighted checks to the suppliers approved version. 

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
I increased layers of security by implementing HTTPS with self-signed certificates, ensuring encrypted communication, and by adding a SHA-256 checksum to verify data integrity. These steps combined confidentiality and integrity protection within the application. In the future, I would continue using OWASP Dependency Check to assess vulnerabilities. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
I verified the application’s functionality through manual testing. I ran the Spring Boot aplication on my local machine and checked for different input and obsure activty. I also re-ran security scans to confirm that no new vulnerabilities were introduced.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
Some of the most helpful resources and tools I used were Java Keytool for certificate generation, Spring Boot security libraries, and OWASP Dependency Check for identifying vulnerable dependencies. These same tools and principles will continue to be valuable in any secure software development project.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
From this project, I could show employers my secure REST API implementation that demonstrates both encryption and data verification using SHA-256 and HTTPS. This assignment highlights my ability to perform a vulnerability assessment, apply secure coding practices, and refactor existing code to meet security requirements.
 

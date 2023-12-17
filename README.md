# CS-305

### 1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company specializing in personalized financial plans. The client sought assistance from Global Rain, my employer, to modernize their operations and enhance the security of their web application. The specific issue addressed was the need for added security measures, including file verification and secure communications, to protect sensitive financial information during data transfers.

### 2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I effectively identified and addressed software security vulnerabilities by recommending the use of asymmetric encryption, specifically the SHA-256 algorithm, for file verification. Coding securely is crucial as it safeguards against unauthorized access and protects sensitive information. Software security adds significant value to a company's overall wellbeing by preventing data breaches, maintaining customer trust, and avoiding legal and financial repercussions associated with compromised data.

### 3. What part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the vulnerability assessment was ensuring the code remained both functional and secure after refactoring. The helpful aspect was the guidance provided by the Vulnerability Assessment Process Flow Diagram, which facilitated a systematic approach to identifying and addressing security issues.

### 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security layers by deploying asymmetric encryption, generating self-signed certificates, implementing cryptographic hash algorithms, and converting HTTP to HTTPS. In the future, I would continue using tools like OWASP Dependency-Check Maven for static testing and follow industry best practices. Regular vulnerability assessments and staying informed about emerging threats would guide the selection of mitigation techniques.

### 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I ensured functionality and security through various steps, including deploying cryptographic hash algorithms, verifying secure communications, and running both secondary and functional testing using OWASP Dependency-Check Maven. To check for new vulnerabilities, I performed regular dependency checks, focusing on the code added during refactoring, and iterated the design until no new vulnerabilities were found.

### 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I utilized the Java Keytool for certificate generation, SHA-256 algorithm for secure hashing, and OWASP Dependency-Check Maven for static testing. The practice of organizing code, careful handling of input, and regular dependency checks are valuable coding practices that would be beneficial in future assignments.

### 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I can showcase my expertise in implementing secure coding practices, utilizing industry-standard encryption algorithms, and conducting thorough vulnerability assessments. Additionally, I can demonstrate my ability to address client requirements effectively, enhance software security, and maintain functional applications in a dynamic environment.

# CS 305 Portfolio Artiface Reflection

## Artifact: Artemis Financial Practices for Secure Software Report

Artifact Overview

The client for this project was Artemis Financial, a financial services company that required improvements to the security of its web application. The company wanted to ensure that sensitive financial data could be 
transmitted securely and that the application was protected from common software vulnerabilities. The primary issue was identifying security weaknesses within the existing application and implementing secure coding 
practices to mitigate those risks.

One of my strengths during this project was identifying software vulnerabilities and applying appropriate security measures to address them. I conducted a vulnerability assessment, analyzed dependency reports, 
implemented secure communications through HTTPS, generated a self-signed certificate, and refactored code to use the SHA-256 cryptographic hash algorithm for checksum verification. Secure coding is important 
because it helps protect sensitive information, reduces the likelihood of cyberattacks, and maintains customer trust. Strong software security also reduces financial and reputational risks for organizations.

The most challenging aspect of the project was interpreting vulnerability scan results and distinguishing between legitimate vulnerabilities and false positives. However, this process was also one of the most 
valuable learning experiences because it demonstrated how security professionals must carefully analyze findings before implementing mitigation strategies.

To increase layers of security, I implemented HTTPS using SSL/TLS certificates, generated checksum verification using SHA-256 hashing, and reviewed project dependencies using OWASP Dependency-Check. 
In future projects, I would continue using vulnerability scanning tools, secure code reviews, dependency analysis tools, and industry security frameworks to assess risks and determine appropriate mitigation techniques.

To ensure the application remained functional and secure after refactoring, I tested the application after each modification and verified that the code executed correctly. I also performed additional dependency-check 
scans to identify any newly introduced vulnerabilities. This validation process helped confirm that security improvements did not negatively impact functionality.

Several resources and tools used throughout this project will be valuable in future software development work. These include Eclipse IDE, Maven, Java Keytool, OWASP Dependency-Check, SHA-256 cryptographic hashing, 
SSL/TLS certificate management, and secure coding best practices. These tools helped strengthen my understanding of application security and vulnerability management.

If presenting this project to future employers, I would showcase the completed Artemis Financial Practices for Secure Software Report, examples of secure code refactoring using SHA-256 hashing, HTTPS implementation 
with SSL certificates, and documentation demonstrating vulnerability assessment and mitigation activities. These artifacts demonstrate my ability to identify security risks, implement secure coding practices, and 
validate software security improvements.

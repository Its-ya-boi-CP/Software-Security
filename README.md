# Software-Security

## CS 305 Portfolio Reflection

For my CS 305 portfolio artifact, I submitted my completed Artemis Financial secure software report. Artemis Financial was a financial consulting company that needed help improving the security of its web application. The company wanted to protect sensitive client and financial information by identifying software vulnerabilities, improving secure communication, and applying secure coding practices.

One thing I did well was identifying security issues in the application and explaining why they mattered. I reviewed the project dependencies, looked for known vulnerabilities, and used security tools to check the application. Secure coding is important because software that handles financial or personal data must protect users from risks such as data theft, unauthorized access, and weak communication security. Strong software security adds value to a company by protecting customer trust, reducing legal and financial risk, and helping the business operate safely.

The most challenging part of the vulnerability assessment was reviewing the dependency-check report and understanding which vulnerabilities were most important. Some dependencies had multiple CVEs, and it took careful review to understand whether the issue came from a direct dependency or a transitive dependency. This was also helpful because it showed me how important it is to keep libraries, frameworks, and project dependencies updated.

I increased layers of security by adding secure communication through HTTPS, using a certificate, and applying a secure hashing algorithm to verify data integrity. I also considered how dependency updates, secure configuration, and input validation can reduce risk. In the future, I would use tools such as OWASP Dependency-Check, Maven reports, secure coding checklists, and vulnerability databases to assess risks and decide which mitigation techniques are best.

To make sure the code and application were functional and secure, I tested the application after making changes and confirmed that it still ran correctly. After refactoring the code, I ran the application again, checked that the secure webpage loaded properly, verified the checksum output, and reviewed the dependency-check report to see whether new vulnerabilities were introduced. This helped confirm that the security changes did not break the application.

Some resources, tools, and coding practices I used that will help me in future work include Java, Spring Boot, Maven, Java Keytool, HTTPS/SSL certificates, SHA-256 hashing, OWASP Dependency-Check, and secure coding practices. These tools helped me understand how to find vulnerabilities, protect communication, and improve application security.

I could show future employers my Artemis Financial report as an example of my ability to review software security, identify vulnerabilities, use security tools, and improve a software application. This assignment shows that I understand the importance of secure coding and that I can apply security practices in a real software development project.

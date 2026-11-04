# CS 305 Portfolio Project: Artemis Financial Software Security

## Project Summary

For this project, I worked with Artemis Financial, a financial consulting company that creates individualized financial plans for its customers.

The goal was to improve the security of an existing software application and better protect sensitive customer and financial information. The application needed secure communication and a method for verifying that transmitted data had not been altered.

## Security Improvements Implemented

- Configured HTTPS for secure communication
- Created and applied a self-signed certificate
- Added SHA-256 checksum verification
- Used OWASP Dependency-Check to identify known vulnerabilities
- Reviewed existing application dependencies
- Refactored the application while maintaining functionality
- Tested the application after security changes

## Technologies and Tools Used

- Java
- Spring Boot
- Maven
- Eclipse
- OWASP Dependency-Check
- Java Keytool
- HTTPS
- SHA-256 Hashing
- Digital Certificates
- Manual Code Review

## Vulnerability Assessment

One of the main responsibilities in this project was reviewing the application for security weaknesses and identifying areas where stronger protections were needed.

I used OWASP Dependency-Check to evaluate third-party dependencies for known vulnerabilities. This helped me understand how automated security tools can be used to identify risks within software components.

## Increasing Application Security

I strengthened the application by adding SHA-256 checksum verification, configuring HTTPS, creating a certificate, and using OWASP Dependency-Check.

These changes added multiple layers of protection for data transmission and application integrity.

## Testing and Validation

After refactoring the application, I tested it to make sure it continued to function correctly.

I verified that:

- The application started without errors
- The `/hash` endpoint returned the correct checksum
- The application operated over HTTPS
- Dependency testing still completed successfully
- No obvious new vulnerabilities were introduced through the changes

## Challenges I Faced

One of the more challenging parts of the project was learning how to use OWASP Dependency-Check and understanding which vulnerabilities were connected to the application's existing dependencies.

Working through this process helped me better understand how automated security scanning tools fit into the software development lifecycle.

## What I Learned

This project strengthened my understanding of:

- Secure coding practices
- Software vulnerability assessment
- Dependency management
- Encryption and hashing concepts
- HTTPS configuration
- Certificates
- Security testing
- Code review
- Application testing after refactoring

It also helped me understand the importance of building security into software throughout development rather than treating security as something added only at the end.

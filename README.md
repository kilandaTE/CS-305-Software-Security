# CS-305-Software-Security
## CS 305 Portfolio Reflection

### Artemis Financial and Software Requirements
Artemis Financial is a financial consulting company that creates individualized financial plans for its customers. The company wanted to improve the security of its software application and protect sensitive customer and financial information. The main issue was making sure the application used secure communication and included a way to verify that transmitted data had not been changed.

### Software Security Vulnerabilities
One thing I did well was reviewing the application for security issues and adding protections such as HTTPS, a self-signed certificate, SHA-256 checksum verification, and dependency testing. Secure coding is important because it helps protect sensitive information from being exposed, changed, or accessed by unauthorized users. Software security also helps protect a company’s reputation and maintain customer trust.

### Challenging and Helpful Parts
One of the more challenging parts of the vulnerability assessment was working with the dependency-check tool and understanding which vulnerabilities were related to the existing dependencies. It was also helpful because it showed me how automated security tools can be used to identify known vulnerabilities in software components.

### Increasing Layers of Security
I increased the layers of security by adding SHA-256 checksum verification, configuring the application to use HTTPS, creating a certificate, and using OWASP Dependency-Check. In the future, I would use tools such as dependency scanners, manual code reviews, vulnerability assessment frameworks, and current security standards to determine which vulnerabilities need to be addressed and which mitigation techniques should be used.

### Functional and Secure Code
I tested the application after refactoring it to make sure it still worked correctly. I verified that the application started without errors, confirmed that the `/hash` endpoint returned the correct checksum, and tested the application over HTTPS. I also ran OWASP Dependency-Check again after making changes to help determine whether I had introduced any new vulnerabilities.

### Resources, Tools, and Coding Practices
Some of the tools and practices that were helpful during this course were Java Keytool, SHA-256 hashing, HTTPS configuration, Maven, OWASP Dependency-Check, Eclipse, and manual code review. These tools and practices can also be useful in future software development and security assignments.

### What I Would Show Future Employers
I would show future employers my Practices for Secure Software Report because it demonstrates that I can review an existing application, identify security concerns, add security features, test the application, and document the work I completed. It also shows my experience working with encryption, hashing, HTTPS, certificates, and vulnerability testing.

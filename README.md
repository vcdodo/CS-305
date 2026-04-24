# CS-305 Software Security

## Artemis Financial – Project Summary and Reflection

### Client Summary and Software Requirements
Artemis Financial is a financial services company that manages sensitive client data and provides investment planning tools.

The company requested a security review of its existing software application, focusing on identifying vulnerabilities, strengthening encryption, and ensuring secure data transmission.
The primary issue they wanted addressed was the lack of strong, modern security controls, including outdated dependencies, insecure configurations, and missing encryption on critical endpoints.

### Identifying and Addressing Security Vulnerabilities

#### What I Did Well
I systematically analyzed the codebase and dependency‑check report, identified vulnerabilities with clear CVE references, and documented each issue with recommended mitigation steps. I also validated findings through both manual review and automated scanning, ensuring accuracy and completeness.

#### Importance of Secure Coding

- Secure coding is essential because it:
- Protects sensitive financial and personal data
- Reduces the risk of breaches, fraud, and legal liability
- Preserves customer trust and company reputation
- Ensures long‑term stability and compliance

Strong software security directly contributes to a company’s operational health and overall well‑being.

### Challenges and Helpful Parts of the Assessment

The most challenging part was interpreting dependency‑check results, especially distinguishing between false positives and legitimate vulnerabilities.
The most helpful part was the structured vulnerability assessment process, which provided a clear workflow for identifying, documenting, and mitigating issues.

### Increasing Layers of Security

I strengthened the application by:
- Implementing HTTPS with a properly configured SSL/TLS certificate
- Updating outdated dependencies and removing vulnerable libraries
- Improving input validation and error handling
- Applying secure configuration settings and best practices

In the future, I would continue using tools such as:
- OWASP Dependency‑Check
- Static Application Security Testing (SAST) tools
- Dynamic Application Security Testing (DAST) tools
- OWASP Top 10 and NIST guidelines

These help to determine which vulnerabilities pose the highest risk and which mitigation techniques are most appropriate.

### Ensuring Functionality and Security

To ensure the application remained functional and secure:
- I refactored code incrementally, testing after each change
- I reran dependency‑check scans to confirm no new vulnerabilities were introduced
- I validated SSL configuration and verified secure communication
- I performed manual code review to ensure logic and structure remained intact

This combination of automated and manual verification helped to maintain both stability and security.

### Useful Resources, Tools, and Practices

Throughout the project, I relied on:
- OWASP Dependency‑Check for vulnerability scanning
- Secure coding standards (OWASP, NIST)
- SSL/TLS configuration guides
- IDE tools for code inspection and refactoring

These practices will continue to be valuable in future development and security tasks.

### What I Can Show Future Employers

From this assignment, I can demonstrate:
- The ability to complete a vulnerability assessment report with CVE documentation
- The ability to draft a mitigation plan showing how I addressed each issue
- Evidence of secure coding practices and refactoring
- The ability to implement SSL/TLS encryption
- A clear understanding of software security principles
- The ability to analyze, document, and improve a real‑world codebase

These artifacts highlight my skills in secure development, problem‑solving, and professional documentation.

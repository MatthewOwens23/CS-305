CS 305 : Artemis Financial
Project Summary

Artemis Financial was a financial services company that needed help improving the security of its software application. The goal was to identify security vulnerabilities and make changes to help protect sensitive information. The project involved reviewing the existing code, implementing secure communication, adding a SHA-256 hashing endpoint, and testing the application to make sure it worked correctly.

What I Did Well and Why Secure Coding Matters

I did well with identifying security risks and applying secure coding practices to address them. In Project Two, I configured HTTPS using TLS, created a certificate and keystore, and implemented a SHA-256 hashing endpoint. Secure coding is important because vulnerabilities can expose sensitive information and create opportunities for attackers to compromise a system. For a company like Artemis Financial, good software security helps protect customer information, maintain trust, reduce the risk of financial losses, and support the company's reputation.

Challenges and Helpful Parts of the Assessment

One of the more challenging parts of the project was configuring HTTPS and getting the certificate and keystore set up correctly. I also had to work through dependency vulnerabilities and understand how third-party libraries could affect application security. Testing the application was helpful because it allowed me to verify that the hashing endpoint worked and that the application could communicate over HTTPS. This helped me understand that security involves more than just writing code. Configuration, dependencies, and testing are also important.

Increasing Layers of Security

I increased security by configuring HTTPS on port 8443, setting up a certificate and keystore, and using SHA-256 to generate a hash for the application endpoint. These changes helped protect communication and demonstrate how hashing can be used to verify data integrity. I also used the OWASP Dependency-Check Maven plugin to identify known vulnerabilities in third-party dependencies. In the future, I would continue using dependency scanning, manual code reviews, and security testing. I would also review vulnerability severity, the affected components, and the available fixes before deciding which mitigation techniques to use.

Ensuring Functionality and Security

After making changes to the application, I tested the hashing endpoint through a browser and verified that the application was accessible over HTTPS. I also used Dependency-Check to review known vulnerabilities in the project's dependencies. After refactoring, checking the application's functionality helped me make sure the changes did not break existing behavior. Reviewing the dependency report also helped identify additional risks that needed attention. These steps showed me why security testing should be performed alongside functional testing whenever code is changed.

Tools and Coding Practices

Some of the tools and practices I used were Java, Maven, the OWASP Dependency-Check Maven plugin, HTTPS/TLS, SHA-256 hashing, certificates, and a keystore. I also practiced reviewing code, testing application endpoints, checking dependencies, and documenting security changes. These skills will be useful in future programming assignments and IT work because applications need to be maintained and checked for vulnerabilities throughout their lifecycles.

Applying This Work to My Career

I could show future employers my Artemis Financial Practices for Secure Software Report and the related project code to demonstrate my understanding of secure software development. This project gave me experience with HTTPS configuration, hashing, dependency vulnerability analysis, and application testing. It also helped me understand how security practices can be applied to an existing application rather than just discussed in theory. These are useful skills for an entry-level IT or software development position because they show that I can identify security concerns, make improvements, and test the results.

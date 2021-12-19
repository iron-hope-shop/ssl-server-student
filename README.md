# ssl-server-student
## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client was Artemis Financial, a financial consulting company that developed individualized financial plans for savings, retirement, investments, and insurance for their patrons.  Artemis Financial desired to implement and apply the most current and effective software security.  Namely, they wanted to add a file verification step to their web application to ensure secure communications.

## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I took a step-by-step approach to identify the software security vulnerabilities.  It is important to code securely to maintain the integrity of customers' data and keep their trust.  Software security helps to save money and protect the brand of a company.

## What about the process of working through the vulnerability assessment did you find challenging or helpful?
Reading through a vulnerability report was helpful and challenging.  This is because we had to identify which of those vulnerabilities applied to our application.

## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
We used MD5 as a checksum to verify the file. The algorithm takes as input a message of arbitrary length and produces as output a 128-bit "fingerprint" or "message digest" of the input. It is conjectured that it is computationally infeasible to produce two messages having the same message digest, or to produce any message having a given prespecified target message digest.  Keeping a step-by-step process to assess vulnerabilities and determine mitigation techniques is crucial to security operations.  Additionally, we should monitor information security newsfeeds to stay current on potentially widespread vulnerabilities.

## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
In order to ensure the code and software application were functional and secure, I did local debugging.  Part of that debugging was generating new vulnerability reports and addressing vulnerabilities which were still present.

## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I was not aware of the OWASP dependency check package in Spring Boot Java.  I will continue to use it and find a similar package for other languages I employ.

## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would want to showcase the research, identification, and implementation of security techniques to prevent vulnerabilities.  Vulnerabilities are common, and in recent years the number of vulnerabilities has increased. Best practices for maintaining security and resilience. They offer additional insights into the role of the physical and cyber security industries in mitigating such threats, helping researchers to more effectively address security challenges that arise when critical systems become vulnerable. Being secure, the company will continue to have the power to provide for and serve its customers for the long term, not just the short-term.

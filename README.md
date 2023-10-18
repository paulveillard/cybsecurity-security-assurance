# Security Assurance: Theory, Techniques, and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Security Assurance in Cybersecurity
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources

# Theory

## `Theory` - Table of Contents
- [Introduction](#introduction)
- [What is Security Assurance ](#what-is-security-assurance)



##  `What is Security Assurance? `
- A security assurance can be defined as the confidence that a system meets its security requirements and is resilient against security vulnerabilities and failures. The confidence indicated by the security assurance represents the level of trust we give to a system that is safe to use.

### NIST & CNSSI Standards Definition

#### CNSSI 4009

> Measure of confidence that the security features, practices, procedures, and architecture of an information system accurately mediates and enforces the security policy

#### NIST SP 800-53

> Ground for confidence that the set of intended security controls in an information system are effective in their application

## Introduction

Security assurance is an umbrella term for several processes aimed at ensuring individual system components can adequately protect themselves from attacks. Doing so requires not just a one-time effort, but actually spans the complete system lifecycle. After all, what is considered an acceptable security posture may change over time depending on, for example, newly emerging threats or changes to how the system itself is utilized.


We summarize the key processes that should be part of every security assurance program as follows:

- Security Hardening
- Security Testing
- Vulnerability Management

In the remainder of this article, let’s take a closer look at what these individual processes entail.

#### Security Hardening
Security hardening describes the minimization of a system’s attack surface and proper configuration of security functions. The former may be achieved by disabling unnecessary components, removing superfluous system accounts, and closing any communication interfaces not in use – just to name a few. The latter configuration task focuses on security controls within the system itself and ensures that these can perform their functions as intended. This can include the configuration of host-based firewalls, intrusion detection/ prevention capabilities, or operating system controls, such as SELinux.

> Security hardening is particularly important before a system is deployed, but should be verified regularly thereafter to confirm that the system still meets the defined hardening standard in the context of its current operating environment.



#### Security Testing
Security testing aims to validate a system’s security posture by trying to identify any weaknesses or vulnerabilities possibly remaining after security hardening. This activity can take many different forms, depending on the complexity of the system under test and the available resources and skills. In its most basic form, it may comprise an automated vulnerability scan from the outside as well as an authenticated scan from the perspective of a user on the system. More advanced tests would go a step further by analyzing the system’s responses and reasoning about communication flows that may afford an attacker with a way into the system. Established best practices, such as the OWASP Top 10, can serve as a useful guide here to focus the test activities on the most common vulnerabilities. Beyond that, fully manual test could dig even deeper, for example, trying to discover vulnerabilities in the systems source code if available.

> Similar to hardening of the system, security testing should also be performed before and during a systems operation. Regular, automated security scans can be a great tool to identify new vulnerabilities early on



#### Vulnerability Management
Vulnerability management takes the results of the security tests performed and attempts to mitigate them. This includes the analysis of each finding (Is this actually an issue in the context of this system?), prioritization (How big of an issue is it?), and mitigation (How can it be fixed?). While the last part should be fairly obvious, the first two are just as essential since it is important to take a risk-based approach to vulnerability mitigation. No system will ever be completely free of vulnerabilities, but the goal should be to avoid the ones that are critical and easily abusable



## Improving Security Assurance
So, what are some ways we can work towards improving security assurance and prepare our systems for the threats to come in the future?

### 1) Find a balanced approach

As mentioned, with secure development and maintenance of products, organizations can do a great deal of work toward ensuring the product’s security. This should be considered in the evaluation, providing a more integrated and holistic approach. Assurance measures in the development cycle should be better recognized, and assessments should promote development assurance.


### 2) Collaborate and communicate with transparency
To achieve a more balanced approach as described above, we need to see more communication and training so that developers and evaluators can understand each other better and work together to optimize the process. Software engineers often build in many layers and at high levels of complexity, meaning evaluators with little or no development background will be poorly equipped to evaluate the value of the developers' contributions. However, it’s important to remember that requirements like development expertise for evaluation will come with a higher cost.

Regardless of the approach, when undertaking evaluation, developers need to be transparent and communicative. Tell evaluators what you’re doing and how you’re doing it. Don’t try to create an alternative reality for auditing – if the evaluators offer suggestions for improvement, they want to improve your real processes and not artificial ones that have been submitted.

> If security assurance is to take a more holistic approach, we need to find a compromise that accommodates the needs of both the developers and the evaluators, while remaining efficient and cost-effective for the level of assurance required. We need to clarify what the roles and responsibilities should be in this process. Right now, confusion remains over who should do the testing or vulnerability analysis. But both sides must be involved – they just have different roles to play in the process.

### 3)  Prepare for complexity with layers and diversity

The sophisticated attackers we face today are constantly looking to inject vulnerabilities or malware into the supply chain. Unfortunately, many companies aren’t currently putting enough emphasis on supply chain security. While it isn’t cost-effective for most companies to build up their own supply chain for complex systems, leaving them reliant on third-party components or software, diversity can offer a work-around solution. You shouldn’t put trust in just one service or component, but you might be able to achieve sufficient security assurance by combining different security layers from different suppliers or nations – one from the US, one from China, for example. For your system to be broken, they then need to talk to each other – and most likely, they won't.


## `Techniques` - Table of Contents

## `Tools` - Table of Contents




## License
MIT License & [cc](https://creativecommons.org/licenses/by/4.0/) license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

To the extent possible under law, [Paul Veillard](https://github.com/paulveillard/) has waived all copyright and related or neighboring rights to this work.
The underlying source code used to format and display that content is licensed under the MIT license.

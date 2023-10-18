# Security Assurance: Theory, Techniques, and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Security Assurance in Cybersecurity
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources

# Theory

## `Theory` - Table of Contents
- [Introduction](#introduction)
- [What is Security Assurance ](#what-is-security-assurance)



##  `What is Security Assurance? `

### Assurance

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







## `Techniques` - Table of Contents

## `Tools` - Table of Contents




## License
MIT License & [cc](https://creativecommons.org/licenses/by/4.0/) license

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

To the extent possible under law, [Paul Veillard](https://github.com/paulveillard/) has waived all copyright and related or neighboring rights to this work.
The underlying source code used to format and display that content is licensed under the MIT license.

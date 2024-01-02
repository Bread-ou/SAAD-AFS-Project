# 6. Adopting SOA/Service-Based Architecture 

Date: 18-12-2023

## Status

Accepted

## Context

When developing a software system, it is imperative to select an architectural style suitable for the solution.Software Architecture dictates the high-level organization of the system's components and how they interact with one anotherr.  Software architecture is needed to build a solid foundation for the application, 
and it ensures that the application meets its functional and non-functional requirements and needs for both users and stakeholders (1). With 

## Decision

Given that the application is designed to cater to a vast number of users globally, the key non-functional requirements (NFRs) to prioritize are:

* Security
* Compliance
* Internationalization
* Scalability
* Availability
* Usability
* Accessibility

The emphasis here leans towards expanding reach, ensuring broad applicability, and scalability, rather than concentrating on performance or catering to a specialized user base.

## Consequences

* **Wider Accessibility and Market Reach:** Prioritizing internationalization, compliance, and availability allows for the system to be more accessible to users in different regions and time zones, potentially increasing its market reach. However, this requires additional resources to support multiple languages, cultures, and regional standards.
* **Enhanced Security and Trust:**  The focus on security will help protect user data and prevent breaches, fostering trust among users. Given that the application will manage highly sensitive user data, including passports and national IDs, establishing and maintaining trust is essential for the software's success.
* **Performance Loss:** Given the aforementioned NFRs selected for this project, the system will suffer in other areas. Maximizing the security, accessibility, and usability of the application will impede the system's performance.

## References 

*

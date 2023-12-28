# 4. Choosing Which Arcgutectural Style to Follow

Date: 08-12-2023

## Status

Accepted

## Context

In developing a software application, numerous non-functional requirements (NFRs) can be considered. However, meeting these NFRs demands significant resources, and sometimes, certain NFRs may conflict with each other. Therefore, it is best to prioritize a select few NFRs, which helps provide a clear focus on what is most integral to the software's overall goal.

**NFRs include but are not limited to:**
* Performance
* Capacity
* Availability
* Security
* Manageability
* Usability
* Accessibility
* Scalability
* Compliance
* Data Integrity
* Efficiency 

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

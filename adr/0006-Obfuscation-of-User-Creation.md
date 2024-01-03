# 7. Abstracting The Methods by Which Visa Officers and Administrators are Created

Date: 15-12-2023

## Status

Accepted

## Context

This project has already highlighted that there is a login and account creation mechanism, however methods of account creation were only highlighted for 3 of the 5 users; that being the Applicant, Visa Advisor, and the Branch Manager.
There was no indication in the requirements as to how the Visa Officer and Administrators create their account.

## Decision

Keeping the

## Consequences

* **Modularity:** SOA modularity allows for flexibility and agility when adapting new technologies and integrating them within the system.
* **System Resilience:** Errors occurring in the system will be localized to the specific component that's faulty instead of the entire solution; this strengthens the resilience of the system. 
* **Adding Complexity:** The modularized components will require a comprehensive network of communication to allow for the system to function as a unit, which will add complexity to the solution.

## References 

* Hou, Xs. (2023, August 30). 12 software architecture Styles Software Engineer should know. Medium. https://medium.com/@xsronhou/12-software-architecture-styles-software-engineer-should-know-ee92e3b1f9ac 

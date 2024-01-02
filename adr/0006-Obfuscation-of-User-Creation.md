# 7. Abstracting The Methods by Which Visa Officers and Administrators are Created

Date: 15-12-2023

## Status

Accepted

## Context

The AFS system requires users to sign-in to access the

## Decision

SOA was selected for its modular nature, enhancing application security and reusability. For instance, the visa application component will only need to be accessed by Visa Officers and Applicants.
The visa application component has a dedicated database to limit the scope of data each service can access, which will enhance security. The splitting of components and limiting of scope align well
with the principles of SOA, where services are loosely coupled and highly cohesive, allowing for independent scaling and optimization according to the specific requirements of each component.

## Consequences

* **Modularity:** SOA modularity allows for flexibility and agility when adapting new technologies and integrating them within the system.
* **System Resilience:** Errors occurring in the system will be localized to the specific component that's faulty instead of the entire solution; this strengthens the resilience of the system. 
* **Adding Complexity:** The modularized components will require a comprehensive network of communication to allow for the system to function as a unit, which will add complexity to the solution.

## References 

* Hou, Xs. (2023, August 30). 12 software architecture Styles Software Engineer should know. Medium. https://medium.com/@xsronhou/12-software-architecture-styles-software-engineer-should-know-ee92e3b1f9ac 

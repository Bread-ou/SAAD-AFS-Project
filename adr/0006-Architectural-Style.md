# 6. Adopting SOA/Service-Based Architecture 

Date: 18-12-2023

## Status

Accepted

## Context

When developing a software system, it is imperative to select an architectural style suitable for the solution. 
The establishment of a software architecture is crucial, as it forms the fundamental structure of an application (Hou, 2023). 
It outlines the system's component organization and their interactions, ensuring that both functional and non-functional requirements are met. 
A strong architectural foundation is vital for satisfying the needs of users and stakeholders. 
Inspired by insights from XSron Hou's discourse on architectural paradigms, we have identified various architectural styles to consider for our application:

* **Monolithic:** A way of structuring an application as a single, cohesive unit, rather than splitting it up into smaller components.
* **Microservice:** Structures the application as a collection of small, independent services that communicate with each other over a network.
* **Event Driven:** a style focused on communication between components or services. In this paradigm, different software components communicate with each other using events, rather than through direct requests or responses.
* **SOA:** A structure aimed at modularising components, allowing for reusability and scalability. Allows for the building of specific pieces of functionality and then combining them to create a larger system.

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

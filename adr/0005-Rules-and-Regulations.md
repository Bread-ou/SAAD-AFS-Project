# 5. Choosing to Externalize The Rules and Regulations Gathering Functionality  

Date: 10-12-2023

## Status

Accepted

## Context

While developing the C4 system context diagram and analyzing project requirements, a critical issue emerged. The system displays travel guidelines for various countries, but these guidelines frequently change. To maintain accuracy, the system must incorporate a mechanism for updating these rules. This necessitates either integrating a component within the system to manage updates or considering the exclusion of this feature from the system's scope due to its dynamic nature.

## Decision

Given that displaying the rules is the required functionality and not the mechanism to update rules, this functionality has been excluded and is treated as an external system. This is shown in the system context diagram.


## Consequences

* **Simplifying Architecture:** The architecture of the system will be simpler as the functionality is outsourced, allowing for resources to be allocated elsewhere.
* **Reliability of Information:** The system will be reliant on an external source for accurate and up-to-date travel information. As a result, the system will lack control over the accuracy and availability of this information.
* **Dependency:** The system is completely  dependent on the external source for travel and visa information. Therefore, the system is unable to provide the information required in the event the external source fails.








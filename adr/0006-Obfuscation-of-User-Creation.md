# 6. Abstracting the Account Creation Process for Visa Officers and Administrators

Date: 15-12-2023

## Status

Accepted

## Context

Our project includes a login and account creation mechanism, primarily outlined for Applicants, Visa Advisors, and Branch Managers. 
However, the methods for account creation for Visa Officers and Administrators were not detailed in the initial requirements.

## Decision

Given that the account creation process is not a critical function of the roles of Visa Officers and Administrators, it has been decided to abstract this aspect. 
Introducing specific account creation methods for these roles would complicate the network, requiring verification of qualifications and additional security measures. 
As this does not directly contribute to the main objectives of the solution, the decision is to streamline the process by not explicitly detailing these methods.

## Consequences

* **Simplicity:** The abstraction of the user creation methods leads to a simpler solution as there is less functionality to account for.
* **Future Problems:** Although simpler, the current solution would not be deployable. Future changes are needed to address the issue as it is still necessary for real-world applications.

# 5. Choosing a Website Theme Accomadting for People with Colour Blindness 

Date: 20-12-2023

## Status

Accepted

## Context

When creating a website, factoring in the needs of all users, including those with accessibility requirements,
is crucial. Colour blindness, impacting about 1 in 12 men and 1 in 200 women (1), significantly impacts how users interact with online platforms.
Intending to cater to a wide audience, the AFS solution will adhere to a colour palette  that accommodates colour blindness.
This approach will greatly elevate the solution's accessibility and reach.

## Decision

Following the guidance set by a tableau blog on designing colour-blind-friendly visualizations,
the solution will adopt a palette combining dark blue and light grey, with orange as an accent colour.
This choice of colours will make the website more accessible to individuals with protanopia and deuteranopia. 
In cases of people with tritanopia, the contrast of the colours and the orange 
accent should help with distinguishing between the different artefacts.

## Consequences

* **Simplifying Architecture:** The architecture of the system will be simpler as the functionality is outsourced, allowing for resources to be allocated elsewhere.
* **Reliability of Information:** The system will be reliant on an external source for accurate and up-to-date travel information. As a result, the system will lack control over the accuracy and availability of this information.
* **Dependency:** The system is completely  dependent on the external source for travel and visa information. Therefore, the system is unable to provide the information required in the event the external source fails.

## References 
* https://www.colourblindawareness.org/colour-blindness/
* https://www.tableau.com/en-gb/blog/examining-data-viz-rules-dont-use-red-green-together#:~:text=For%20example%2C%20blue%2Forange%20is,palette%20designed%20by%20Maureen%20Stone.

---
layout: default
---
# Three-tier Architecture

Everest is designed on the Microsoft ® Windows ® DNA Architecture (now known as Microsoft's Web Solution Platform). It comprises the following three tiers:

* Presentation Services Tier
* Business Services Tier 
* Data Services Tier

The **presentation services tier** is responsible for: 

* Gathering information from the user. 
* Sending the user information to the business services for processing.
* Receiving the results of the business services for processing. 
* Presenting those results to the user. 

The **business services tier** is responsible for: 

* Receiving input from the presentation tier. 
* Interacting with data services to perform the business operations that the application was designed to automate.
  * **Example:** Income tax preparation, Order processing.
* Sending the processed results to the presentation tier. 

The **data services tier** is responsible for: 

* Storage of data
* Retrieval of data
* Maintenance of data
* Integrity of data

Click [here](visual-representation-of-everest-three-tier-architecture.html) to view a visual representation of Everest’s Three-tier Architecture

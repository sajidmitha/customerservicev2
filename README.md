# customerservicev2

Customer Service REST API (RAML +Mulesoft)

Date: 12/02/2018 <BR>
Solution Deliverables : <BR><BR>
  
  Integration Specification : Integration Spec -CustomerAPI v1.0.doc <BR>
  Code Base : Anypoint workspace [customerservicev2] <BR>
  Deployed in Cloud : http://customerservicev2.cloudhub.io/api/customers <BR>
  Mock Service : https://mocksvc.mulesoft.com/mocks/12bb4c53-de2f-42a4-a16f-dad240c9e511/customers/ <BR>

<BR><BR>
Requirement: <BR>
Design a RESTful API using RAML that contains a single resource, customers, and allows the following:
 
1.	List customers
2.	Create a new customer
3.	Update a customer
4.	Deletes a customer
 
You may constrain the customer object to first name, last name and addresses, and the format to JSON. 
 
The API must be designed to support the following consumer use cases at a minimum:
1.	A consumer may periodically (every 5 minutes) consume the API to enable it (the consumer) to maintain a copy of the provider API's customers (the API represents the system of record)
2.	A mobile application used by customer service representatives that uses the API to retrieve and update the customers details
3.	Simple extension of the API to support future resources such as orders and products  
 
Please implement the RESTful API in Mulesoft with test stubs for the consumer and provider systems.
 
The deliverable will be assessed against the following:
•	Best practices for RESTful API design
•	Use of built in aspects of the HTTP protocol (status codes, headers etc)
•	Use of RAML features
•	Efficient use of the network (especially for use case 2)
•	Applicability of the API to the use cases (including edge and exceptional scenarios)
•	Breadth of considerations in the design
•	Code quality (if optional task is attempted)
 
Please deliver the following:
•	The RAML spec itself
•	Commentary on the interaction of use case 1 with the API
•	Commentary on interaction of use case 2 with the API
•	Commentary on how the API could be extended for use case 3
•	Commentary on any 'interesting' design decisions you made (and alternative options considered)
•	Link to git repository where the code is stored along with the README.md

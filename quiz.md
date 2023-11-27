## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

	- These services (SOA) perform a particular business function and are independent. By facilitating communication and interaction between different software systems, it also allows collaboration to achieve common goals. This SOA is an architecture design that organizes software applications as a collection of services. The reusable service is for different business processes or applications. Because of this, it is more efficient to design new systems by using pre-existing services instead of starting from scratch.

2. List and discuss the characteristics of SOA.

	* Service reusability - To minimize redundancy, reusing existing services makes it easier to duplicate code and functionality across departments within an organization.

	* Abstraction - This service in SOA hides the complexity of their implementation details, by providing a simplified interface for interaction.

	* Composability - Services big problems are divided into smaller ones.

	* Loose Coupling – This service is to minimize the dependencies on each other and design to operate independently to each other.

	* Autonomy 
	* Standardized Service Contracts
	* Statelessness
	* Discoverability
	* Interoperability

3. Define Microservices.

	- Microservices is designed to separate a single application into smaller and more manageable components with the goal of improving flexibility and ease of development and maintenance.


4. List and discuss the benefits of using Microservices.

	* Improved Maintenance - With these independent services, maintenance and updates can be performed without affecting the entire system.

	* Code is easier to update

5. List and discuss the similarities and differences of SOA and Microservices.

	* Similarities 

	Service-Oriented - Both SOA and Microservices are architecture styles that emphasize a service-oriented approach. They can down systems into modular, independently deployment services.

	* Differences

	* Technology Stacks

	SOA - Allows for a more standardized technology stack across services. There's often a common set of protocols and standards.
		 
	Microservices - are different services that can be used in a different programming language, frameworks, and communication protocols.

	* Data Management

	SOA - often uses a shared data model and centralized database.

	Microservices - have their own databases and emphasis is on decentralized database. Each microservices owns and manages its data.


6. Define Web Services.

	- Web Services is a standardized way to interact between different software applications over the internet. They allow simple interactions such as communication and data exchange between different systems, by allowing them to interact and share information in real time. 

7. List and discuss the benefits of using Web Services.

* Interoperability - refers to the ability of different platforms or systems to communicate and exchange data easily. The benefit is that the application is built with different technologies and programming languages so it can easily communicate with each other even if you are using multiple devices.

	* Platform Independence – web services commonly used over the internet by using standard protocols. This allow application to run on different platforms and devices without being tied to specific technology. 

	* Standardized Communication – Web services use standardized communication protocols such as SOAP (Simple Object Access Protocol). This is to promote simplicity and dependability by ensuring the applications communicate in a consistent and well-defined way.

8. List and discuss the characteristics of Web Services.

	*  XML Based – In the context of web services, XML (eXtensible Markup Language) is essential, especially for representing and transferring structured data. Because xml is a standard format for encoding data that is readable by computers and humans.

	* Coarse Gained – In a web service coarse gained is design approach in which the services provided encapsulate, sizable functional units. Rather than handling small, detailed operations, these services handle large tasks or business processes.

	* Support Documents Exchange – In this support documents exchange is one of the characteristics of web services, this usually refers to the ability of web service to exchange the additional files or attachments to the main data payload. It may include documents, images or any binary text data that is important to the business process being sent through the web service.


9. List and discuss the distinct roles in Web Services Architecture.

	* Provider – The role of the provider is the one who is in charge of creating, executing and operating the web services. Also handles incoming requests.

	* Requestor – while the requestor is the one that initiates a request to a web service and sends the request to provider. 

	* Broker – the broker in charge of serving as an intermediary to make communication easier between customers and service providers. This also handles concerns such as security, authentication, and authorization.

10. List and discuss the Web Services Components.

	* SOAP – stands for Simple Object Access Protocol which is used by web services to exchange data and messages between different applications. By depending on a specific message format, this uses xml for exchanging data.

	* WSDL – which stands for Web Services Description Language, is an XML-based language that describes the operations, data types, and functionalities that a web service supports.


	* UDDI – short for Universal Description, Discovery, and Integration, it was designed to give businesses a standardized way for publishing, finding, and integrating with each other's web services. In the set of web services standards include SOAP and WSDL. 


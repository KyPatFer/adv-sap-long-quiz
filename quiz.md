## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
* A collection of several services into a single application to produce a new application process.

2. List and discuss the characteristics of SOA.
* Standardized Service Contracts = Drafting a contract to adhere to particular guidelines or directives in order to provide clear communication via one or more service descriptions.
* Loose Coupling = Dependencies between certain services are important to prevent needless system degradation.
* Service Abstraction = Encapsulating a logic service that the user is unaware of because it should not demonstrate how it will perform its functions.
* Service Reusability = They are recycling current services.
* Service Autonomy = Services has complete control over all of the encapsulated services.
* Service Statelessness = For the purpose of transferring requests from one state to another, all services must be stateless. since it shouldn't retain any information.
* Service Discoverability = Labeling particular tasks to aid in the user's comprehension of the system's operation. in order for the user to quickly become familiar with the features.
* Service Composability = A collection of enormous issues that divided into smaller issues.
* Service Interoperability = In order to provide users with the service they want, services must adhere to standards.

3. Define Microservices.
* Often referred to as the microservice architecture, this architectural approach organizes an application as a group of autonomous, deployable, loosely connected, business capability-focused, and small team-owned services.

4. List and discuss the benefits of using Microservices.
* Independently Deployable = It doesn't need the assistance of other services to deploy.
* Right tool for the Job = Because it's an architecture pattern that will enable developers and users to use the applications they want, it's the right tool. 
* Precise Scaling = It has a running time that allows it to individually deploy each service.

5. List and discuss the similarities and differences between SOA and Microservices.
Differences
* In terms of architecture, Microservices are made to host various services so they can operate independently, whereas SOA is made to share resources among services..
* Services in a SOA share data storage. Although the Microservices may be able to store data independently.
* Microservices communicate via the API layer, while SOA uses the ESB for communication.
* While microservices rely on the bounded context of coupling, service-oriented architectures (SOA) rely on resource sharing.
* Whereas Microservices use REST and JMS, SOA uses protocols.

Similarities
* Both of them provide collection services.
* Both of them are effectively utilized for cloud services.
* In terms of managing and creating applications, they are both architectural approaches.

6. Define Web Services.
* a program that facilitates client-server communication via the World Wide Web using XML as the communications system.

7. List and discuss the benefits of using Web Services.
* Web service administrators grant permission to expose the current code's accessibility over the framework, and other apps are able to utilize the program's accessibility.
* Consistency and programmed relationships with other programming applications are provided by interoperability into the next. It's similar to them exchanging data and administrations with one another.
* To describe displays in the web organization, use all four layers and the institutionalized industry standard show for connection.
* Instead, the low-cost internet of today uses SOAP via the HTTP protocol.

8. List and discuss the characteristics of Web Services.
* Using XML terminates any network since web services are highly interoperable.
* It allows XML messages to be sent to other systems via web API, enabling loosely coupled connections between systems.
* More functionality is provided compared to more specialized services. In order to store a large amount of related data, it combines one or more fine-grained services into a coarse-grained service.
* Synchronous refers to existing web protocols in that the client waits for the response and is served by RPCoriented messaging while Asynchronous is the client who does not wait for the response and often uses document-oriented messaging.
* Supports RPC; it can connect to a web service via language- and platform-neutral web protocols; clients can use XML protocol to access procedures, functions, and methods.
* Facilitate the exchange of documents to enable the transfer of structured data between various systems.

9. List and discuss the distinct roles in Web Services Architecture.
* For clients, the provider develops a web service.
* A client that needs to communicate with a web service is the requestor. 
* To grant the client access to the UDDI, broker uses the application.

10. List and discuss the Web Services Components.
* The protocol used to transfer data between systems is called SOAP.
* A web service called WSDL aids in providing access information.
* UDDI is a frame in XML

1. SOA uses reusable software services for specific business functions like crefit checks, sign-ins, or mortgage processing across enterprises

2. 
- Standardized Services Contracts: SOA abide by standardized contracts describing their purpose, Capabilities, and functionality ensuring clear expression and formal standardized service within the sysytem.
- Loose Coupling: it aim for minimal interdependence fostering specific relationships while reducing reliance between contracts, implementations and consumers.
- Abstraction: Conceal internal logic, reducing unnecessary information proliferation, preserving loose coupling and also enabling flexible service compositions.
Service Reusability: it split logic to maximize reuse potential.
- Autonomy: it is for self-contained logic, promoting reliability, predictability and also independence from external influences.
- Statelessness: It is a services avoids storing data, enhancing scalability, logic agnosticism and facilitating service reuse within designs.
- Discoverability: It is enable discovery via registries using metadata in contracts to convey purpose, capabilities and also huma-readable information.
- Composability: it decompose complex tasks, leveraging reusable components efficiently optimizing execution allowing data exchange contacts.
- Interoperability: is about prioritize using universal standards for broad usage, sometimes overlooked due in practice.

3.Microservices unlike SOA, it can create agile scalable applicaiotns by employing loosely coupled components, enabling idependent updates and cost in scaling.

4. 
- Independently deployable: it can reduces time furstrations, aligning with agile small-teams structures fostering quick contributions and enhancing both speed and morale.
- Right tool for the job: In each component can use specialized tools, unlike the common stack in traditional architectures allowing flexibility optimization and also easier adaptation to evolving technologies.
- Precise Scaling: it can enable precise scaling by independently deploying and scaling specific services reducing infrastructure needs compared to monolithic applications that scale the entire application uniformly.

5.
- Communication: it can use individual communication protocols whereas SOA relies on a common enterprise service bus (ESB) posing potential single-point failure risks and system slowdowns if a service lag.
Interoperability: it prioritize simplicity with lightweight messaging while SOAs accommodate diverse message protocols for interoperability and flexibility.
- Service granularity: it consist of specialized, focused services while SOA includes a spectrum from small to enterprise-wide services.
- Speed: it can prioritize a shared architecture, simplifying development but often running slower, unlike microservices, whice prioritize speed over sharing.

6.Web services are like versatile building blocks, each capable of performing specific tasks independently. They're designed to work together seamlessly, connecting over the internet to create complex systems or applications.

7.
- Exposing the Existing Function on the network: It's enabling HTTP queries sent over the internet to initiate it. It allows you to share the functionality of your current code with other network applications. 
- Interoperability: Web services are intermediaries that facilitate seamless communication and information exchange across many applications, irrespective of their programming languages or technology. 
-Standardized Protocol: This standardization promotes competition that lowers costs and improves service quality by ensuring compatibility and giving businesses a wide range of protocol options. 
- Low Cost Communication: This less expensive method stands in stark contrast to more expensive proprietary systems like EDI/B2B. Furthermore, web services are more flexible than SOAP over HTTP, they may be implemented on other reliable transport technologies, such as FTP, which increases the range of options available to meet various business requirements.

8.
- XML-Based: It removes all networking, operating system, and platform ties. At their essence, web services-based systems are extremely interoperable.
- Loosely Coupled: Interdependencies arise in a tightly connected system when modifications to one of the client or server logic require updates in the other. But because of their loose coupling, web services provide for greater flexibility and less interdependence between components.
- Coarse-Grained: Every method is an operation that, in a business environment, provides a certain capacity. Coarse-grained functionalities should be provided by Java interfaces, in line with more general business requirements.
- Ability to be Synchronous or Asynchronous: Asynchronous operations allow the client to initiate the service and proceed with other tasks, whereas synchronous operations in services necessitate waiting for the operation to conclude before proceeding.
- Supports Remote Procedure Calls (RPCs): In order to ensure compatibility and comprehension between the client and the service being contacted, these remote procedures define the methods or operations that are accessible for use and explain the parameters required for input and output.
- Supports Document Exchange: Web services support a broad range of data complexities in their documents, from simple representations like an address, to complicated structures like whole books or Request for Quotation (RFQ) forms.

9.
- Provider: The provider develops the web service and offers it to client applications seeking to utilize it.
- Requestor: 
A requestor refers to the client application seeking access to a web service. This application, regardless of its programming language like .Net, Java, or others, aims to utilize the web service's functionalities to fulfill specific needs or tasks.
- Broker: The broker serves as the intermediary application granting access to the UDDI. Through the UDDI, it allows client applications to find and identify the location of the desired web service.
- Publish: Usually via the broker's publish interface, the provider notifies the broker of the web service's availability. By declaring its presence in the service registry that the broker maintains, this action makes the service available to clients.
- Find: The requestor seeks guidance from the broker to find an advertised web service.
- Bind: The requestor can connect to or invoke the web service's features by using the information obtained from the broker; this process is known as binding or invocation.

10.
- SOAP: SOAP is an XML-based protocol that makes data transfer between computers easier. It acts as a common means of communication, facilitating the smooth exchange of data between various systems.
- WSDL: is intended to describe the intricacies of web services, including their features and methods of interaction. It functions as a detailed blueprint that outlines the procedures and organizational framework needed to access and make use of various web services.
- UDDI: provides a standardized framework for defining, promoting, and finding web services. It offers an organized way to list and find web services that are accessible over a network or system.
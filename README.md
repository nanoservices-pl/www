# [About nanoservices](https://www.nanoservices.pl/)

## Hashtags:
+ SOA Service Oriented Architecture
+ Atomisation
+ Modularity
+ nanofrontends


# Nanoservices

## What are nanoservices?

As a result, there are conflicting schools of thought around how and when to use microservices.
First, the mere nature of nanoservices poses the question as to whether they are secured from attack vectors when used extensively in an application.
Some also consider nanoservices to be an anti-pattern due to their fragmented functionality. This is known to cause maintenance overhead to exceed the value of the framework’s benefits.

Certain use cases highlight that, without thorough due-diligence and efficient planning, random expansion of services may end up making the framework as big and cumbersome as a monolithic architecture.


## Simplify

While they are smaller, flexible, more isolated, and functionally focused, there are still unknowns on:
+ Compatibility with emerging tech
+ Exponential scaling
+ nanoservices are designed to perform a single function, whose output is exposed through a specific API endpoint (command).
+ nanoservices are considered smaller siblings of microservices. 
+ Nanoservices are fully discoverable among each other.
Each one can link with other services to perform additional actions and extend functionality.

As nanoservices are still in their infancy, conservative and large organizations usually avoid them (for now), mostly due to the framework’s uncertain support for scalability. 
For those who adopt it, one best practice of using the framework is:
Avoid nanoservices if its use complicates the system that it’s meant to simplify.



## By design, nanoservices are:
+ Self-contained
+ Reusable
+ Less complex than microservices
+ Supported by distinct function files for each

## Efficiency of nanoservices
Nanoservices are considered more efficient than microservices, particularly due to:
+ Ease of initial setup
+ Reduced latency among services

Each nanoservices function code can be executed on-demand without the use of dedicated containers or servers to host every individual service.


## Architecture
https://vmblog.com/archive/2020/02/25/an-introduction-to-serverless-architecture.aspx

## The way of development

Monolith - Microservices - Nanoservices

More Reusability from code side and business logic
With microservices are coming microfrontends
With nanoservices are comming nanofrontends


## Example Code

	test
	
The illustration below highlights an interesting use-case of how the BBC website uses 1,000s of nanoservices to render dynamic web pages.
Each service functions to feed into a specific component of the webpage, such as:
+ Generating a headline
+ Sourcing weather data
+ Updating a match score	


## The Difference Between APIs and Microservices

https://www.scalyr.com/blog/api-vs-microservices/

https://wisdomplexus.com/blogs/nanoservices-vs-microservices/

Here are the main differences between APIs and microservices:

+ An API is a contract that provides guidance for a consumer to use the underlying service.
+ A microservice is an architectural design that separates portions of a (usually monolithic) application into small, self-containing services.
    

# Microservices

## When to use microservices

Compared to nanoservices, microservices are an established and well-known design approach that can operate with a wide range of technologies.

That means microservices have a plethora of resources and groups to support learning or maturity microservices strategy.
Microservices are usually a good fit for:
+ An agile development process
+ Situations where development teams are functionally or geographically distributed
+ Creating a minimum viable product (MVP) that you will extend functionally over time, not all at once


With that in mind, it is equally important to note that microservices are not suited for every application type. 

https://www.bmc.com/blogs/microservice-vs-nanoservice

# SOA

SOA, or service-oriented architecture, defines a way to make software components reusable and interoperable via service interfaces. Services use common interface standards and an architectural pattern so they can be rapidly incorporated into new applications.  
This removes tasks from the application developer who previously redeveloped or duplicated existing functionality or had to know how to connect or provide interoperability with existing functions.

Each service in an SOA embodies the code and data required to execute a complete, discrete business function (e.g. checking a customer’s credit, calculating a monthly loan payment, or processing a mortgage application). 
The service interfaces provide loose coupling, meaning they can be called with little or no knowledge of how the service is implemented underneath, reducing the dependencies between applications. 

This interface is a service contract between the service provider and service consumer. Applications behind the service interface can be written in Java, Microsoft .Net, Cobol or any other programming language, supplied as packaged software applications by a vendor (e.g., SAP), 
SaaS applications (e.g., Salesforce CRM), or obtained as open source applications.  Service interfaces are frequently defined using Web Service Definition Language (WSDL) which is a standard tag structure based on xml (extensible markup language).  

The services are exposed using standard network protocols—such as SOAP (simple object access protocol)/HTTP or Restful HTTP (JSON/HTTP)—to send requests to read or change data. Service governance controls the lifecycle for development and at the appropriate stage the services are published in a registry that enables developers to quickly find them and reuse them to assemble new applications or business processes.


## Benefits of SOA

Compared to the architectures that preceded it, SOA offered significant benefits to the enterprise:

### Greater business agility; 

faster time to market: Reusability is key.  The efficiency of assembling applications from reusable services - i.e. building blocks, rather than rewriting and reintegrating with every new development project, enables developers to build applications much more quickly in response to new business opportunities. The service oriented architectural approach supports scenarios for application integration, data integration, and service orchestration style automation of business processes or workflows.  This speeds software design and software development by enabling developers to spend dramatically less time integrating and much more time focusing on delivering and improving their applications. 
    
### Ability to leverage legacy functionality in new markets: 
A well-crafted SOA enables developers to easily take functionality ‘locked’ in one computing platform or environment and extend it to new environments and markets. For example, many companies have used SOA to expose functionality from mainframe-based financial systems to new web applications, enabling their customers to serve themselves to processes and information previously accessible only through direct interaction with the company’s employees or business partners.

### Improved collaboration between business and IT: 

In an SOA, services can be defined in business terms (e.g., ‘generate insurance quote’ or ‘calculate capital equipment ROI’). This enables business analysts to work more effectively with developers on important insights—such as the scope of a business process defined using services or the business implications of changing a process—that can lead to a better result.


### SOA and microservices

SOA vs. microservices

Experts have filled a few thousand print and digital pages comparing SOA and microservices, and defining the subtleties of their relationship to one another. For the purposes of this article, the chief differences between the two are the coupling of components and scope of use:

    SOA is an integration architectural style and an enterprise-wide concept. It enables existing applications to be exposed over loosely-coupled interfaces, each corresponding to a business function, that enables applications in one part of an extended enterprise to reuse functionality in other applications.
    Microservices architecture is an application architectural style and an application-scoped concept. It enables the internals of a single application to be broken up into small pieces that can be independently changed, scaled, and administered. It does not define how applications talk to one another—for that we are back to the enterprise scope of the service interfaces provided by SOA.

Microservices architecture emerged and gained steam with the rises of virtualization, cloud computing, Agile development practices, and DevOps. Most of the advantages of microservices in these contexts arise from the decoupling of the components, which simplifies and improves the following:

    Developer agility and productivity: Microservices enable developers to incorporate new technologies to one part of the application without affecting the rest of the application. Any component can be modified, tested, and deployed independently of the others, which speeds iteration cycles.
    Scalability: Microservices can take maximum advantage of cloud scalability—any component can be scaled independently of the others for the fastest possible response to workload demands and the most efficient use of computing resources.
    Resilience: Again, thanks to decoupling, the failure of one microservice does not impact the others. And each microservice can perform to its own availability requirements without staking the other components or the entire application to greatest common availability requirements.

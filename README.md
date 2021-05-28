# www
About nanoservices

What are nanoservices?
The basic difference between the two frameworks is that nanoservices are considered smaller siblings of microservices. Nanoservices are designed to perform a single function, whose output is exposed through a specific API endpoint (command).
Nanoservices are fully discoverable among each other. Each one can link with other services to perform additional actions and extend functionality.
By design, nanoservices are:
	• Self-contained
	• Reusable
	• Less complex than microservices
	• Supported by distinct function files for each
Nanoservices are considered more efficient than microservices, particularly due to:
	• Ease of initial setup
	• Reduced latency among services, where each nanoservices’ function code can be executed on-demand without the use of dedicated containers or servers to host every individual service.
Nanoservice real world use case
The illustration below highlights an interesting use-case of how the BBC website uses 1,000s of nanoservices to render dynamic web pages. Each service functions to feed into a specific component of the webpage, such as:
	• Generating a headline
	• Sourcing weather data
	• Updating a match score

When to use microservices
Compared to nanoservices, microservices are an established and well-known design approach that can operate with a wide range of technologies.
There are several successful use-cases of major industry players—Netflix and AWS—who already use microservice architecture to offer several state-of-the-art services. That means microservices have a plethora of resources and groups to support learning or maturity microservices strategy.
Microservices are usually a good fit for:
	• An agile development process
	• Situations where development teams are functionally or geographically distributed
	• Creating a minimum viable product (MVP) that you will extend functionally over time, not all at once
With that in mind, it is equally important to note that microservices are not suited for every application type. Certain use cases highlight that, without thorough due-diligence and efficient planning, random expansion of services may end up making the framework as big and cumbersome as a monolithic architecture.
(Follow microservice best practices from planning all the way through maintenance.)
Nanoservices
Nanoservices are much newer. Proven use cases of their full potential are yet to be discovered. While they are smaller, flexible, more isolated, and functionally focused, there are still unknowns on:
	• Compatibility with emerging tech
	• Exponential scaling
As a result, there are conflicting schools of thought around how and when to use microservices.
First, the mere nature of nanoservices poses the question as to whether they are secured from attack vectors when used extensively in an application.
Some also consider nanoservices to be an anti-pattern due to their fragmented functionality. This is known to cause maintenance overhead to exceed the value of the framework’s benefits.
As nanoservices are still in their infancy, conservative and large organizations usually avoid them (for now), mostly due to the framework’s uncertain support for scalability. For those who adopt it, one best practice of using the framework is:
Avoid nanoservices if its use complicates the system that it’s meant to simplify.


https://www.bmc.com/blogs/microservice-vs-nanoservice

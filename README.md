# Pros of Monolithic Architecture

* One repo, easy to understand

# Cons of Monolithic Architecture

* Development environment with many modules can be hard to maintain.
* Hard to isolate the tests, small change may require the full test run. Bigger the codebase, the longer compile and testing time.
* Continues Deployment is hard to create all the artifacts and running the tests for entire system. Even for a small change
* Scaling is not efficient. If you need to only scale small part of the system with adding extra servers or containers
that will cause to scale entire system. This is not cost efficient.
* Distributing the part of the systems to different teams is hard. Tech stack is being used for the system is tightly coupled. So the team 
assigned to take care of a part of  the system needs to use the same tech stack.

# Pros of Microservices

* Deploy independetly, wont break the not touched parts of the system.
* They are loosely coupled, which allows you to create highly maintainable and testable services.
* Scale independently, no need to pay extra for the parts of the systems won't need upgrade.
* They are focused on business capabilities.
* Each service or set of services can be easily assigned to a dedicated team for code ownership.
* Tech stack can be different for each service
* If one of the services fails, other services can continue to be used.

# Cons/Challenges of Microservices

* Interservice communication stability is imperative to providing data consistency among services. (gRPC helps to improve the speed)
* Data consistency

# Scale Cube and Microservices

Here is the link for scale cube reference -> https://microservices.io/articles/scalecube.html which is also referring to book called The Art of Scalability.

![Screenshot 2024-08-03 at 17 38 00](https://github.com/user-attachments/assets/d9a583f1-e915-4c3e-a638-f26876533079)

# Indicators to Moving from Monolithic to Microservices

* Scalability problems
* Less productive development
* Long release life cycles

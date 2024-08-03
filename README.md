# Pros of Monolithic Architecture

* One repo, reasy to understand

# Const of Monolithic Architecture

* Development environment with many modules can be hard to maintain.

* Hard to isolate the tests, small change may require the full test run. Bigger the codebase, the longer compile and testing time.

* Continues Deployment is hard to create all the artifacts and running the tests for entire system. Even for a small change

* Scaling is not efficient. If you need to only scale small part of the system with adding extra servers or containers
that will cause to scale entire system. This is not cost efficient.

* Distributing the part of the systems to different teams is hard. Tech stack is being used for the system is tightly coupled. So the team 
assigned to take care of a part of  the system needs to use the same tech stack.

# Pros of Microservices

* Deploy independetly, wont break the not touched parts of the system.

# Cons of Microservices

* Interservice communication stability is imperative to providing data consistency among services. (gRPC helps to improve the speed)

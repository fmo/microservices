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
* Data consistency (Sagas are one solution for this https://github.com/fmo/saga-pattern and the other is 2PC(two-phase commit) - coordinates all the processes that form
distributed atomic trnasactions and determines whether they should be committed or aborted) 

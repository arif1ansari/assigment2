# assigment2
This zip file is having 4 projects inside it i.e. eruekaServer2 , consumer, producer and zuul service.
consumer service internally calling producer service by http://localhost:8765/findemployee and displaying all the records for all employee available at that moment.
consumer service also having Load balancer implemented.
Producer service having facility to add employee into the system, deleting, updating and displaying etc.
 From consumer service we have endpoint http://localhost:8765/checkCircuitBreaker which is internally calling Producer service and if any exception is thrown then its getting handled through the circuit breaker.
 

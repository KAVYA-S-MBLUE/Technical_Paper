# **SCALING**

[Scalability](https://en.wikipedia.org/wiki/Scalability) is the property of a system to handle a growing amount of work by adding resources to the system. It is a property of computers, networks, algorithms, networking protocols, programs, and applications in the field of computing.

## TABLE OF CONTENTS

- INTRODUCTION
- PROBLEM STATEMENT
- SOLUTION
  - VERTICAL SCALING
  - HORIZONTAL SCALING
  - LOAD BALANCERS
  - CONCLUSION

## **INTRODUCTION**

Two of the most important components of software development are Performance and Scalability.

The speed and efficiency of a system under a certain workload in a specific timeframe is referred to as performance. Software quality is measured in terms of performance. Performance describes the ability of a system to respond in a specific amount of time by serving a set of users or handling a specific amount of data.

The ability of software to handle a rapid increase in workload is referred to as scalability. Scalability comes into play whenever performance requirements change or when we are unable to fulfill our performance standards. The increase could be due to the rise in concurrent users, a rise in the volumes of information handled, more specific demands seeking accessibility, and everything else that laid additional strain on the system's resources.

The ability of a system to enhance its performance by adding additional resources, as well as to adapt its performance and efficiency over time in response to changes in application and system processing needs, is referred to as Scalability.
Several factors affect the performance of the system:

- Speed
- Throughput
- Responsiveness
- Availability.

## **PROBLEM STATEMENT**

Two of the most important components of software design are performance and scalability. It used to be a presumption that developers had to compromise performance to create highly scalable software, but this is no longer the case with modern apps. Advanced solutions are now available to maintain software performance as it scales.

## **SOLUTION**

Scalability is constantly adopted to analyze an organization's excessive workload. In order to run operations more effectively, major firms that seem to have a steadily expanding potential customer base utilize scalability. Scaling is a long-term strategy that is implemented in response to an anticipated rise in demand.

### **Vertical Scaling**

Using better or larger capacity resources is referred to as Scaling Up/Vertical Scaling. Vertical scaling, for example, is running a program on a computer with a faster CPU. Scaling up is indeed easy; the same program may be run on a more powerful machine without requiring any modifications. However, because the hardware can only get so much more advanced in a reasonable amount of time, this technique cannot be employed indefinitely. It also becomes more expensive as it progresses to more expensive equipment.

***Example :*** *MySQL and Amazon RDS*

- **PROS**

  - Costs of software are lower.
  - Implemention is simple.
  - The licensing fees are reduced.
  - It reduces energy consumption.
  - The expense of cooling is lower than that of horizontal scaling.
  - The interoperability of the applications is preserved.

- **CONS**
  - There is a restraint in Scaling.
  - Horizontal scaling poses a significantly larger chance of disruption.
  - Power outage and equipment malfunctions are more likely.
  - Future upgradeability has a finite scope.
  - Vendor lock-in is severe.
  - The expense of implementation is high.

### **Horizontal Scaling**

Scaling out/Horizontal scaling is the process of increasing the number of resources available to a system by adding more nodes/resources to it. It is possible to scale horizontally by running an application on numerous machines rather than just one. Scaling out is less expensive because the additional machines can be of the same type. It's simple to do and doesn't require a lot of time. Scaling out without the right application design might result in performance degradation as nodes struggle to communicate with one another.

***Example :*** *Cassandra and MongoDB*

- **PROS**

  - Horizontal scaling is far more straightforward and demands no downtime.
  - Horizontal scaling is also easier to maintain automatically than vertical scaling.
  - No matter how big the instance is, limiting the number of requests it receives at once is essential for the performance.
  - Possessing more instances additionally implies having more redundancy in the unlikely case of a failure.

- **CONS**

  - Depending on the amount of instances/resources you require, the costs will be higher.
  - Without a load balancer, your machines are at risk of being overworked, which could result in an outage.

### **Load Balancers**

The technique of dividing a workload evenly across numerous servers is known as [Load Balancing](https://en.wikipedia.org/wiki/Load_balancing_(computing)). To enhance speed and performance while avoiding downtime, a load balancer routes requests to servers that can efficiently handle them.

The technique of allocating a series of processes over a pool of resources (computing units) with the intent of maximizing their overall performance more productive is known as load balancing in computing. Load balancing can optimize the response time and eliminate disproportionately crowding certain computing resources while other compute terminals are kept idle.

Load balancing software distributes processing load across available servers dynamically, ensuring maximum availability and throughput. This increases overall availability, allowing firms to reach higher levels of performance while potentially lowering expenses.

## **CONCLUSION**

The choices to scale horizontally or vertically is dependent on the data requirement.   From CPU resources to database and storage resources, every aspect of your project must expand. Any component of the scalability challenge that is overlooked might result in unintended downtime or even worse. The best approach could be a combination of vertical scaling to estimate individual instance's optimal performance and then horizontal scaling to manage demand spikes while retaining uptime.

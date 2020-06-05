## What are Some Characteristics of Cloud-Native Systems?

### Microservice oriented
Microservices more closely map business logic to code. These systems can be updated and developed independently. A good example of a Microservice architecture would be a Python AWS Lambda application that uses API Gateway.

### Elastic
Elastic systems can automatically scale to meet increased load without the involvement of humans. These same systems can then scale down again when load diminishes. By eliminating human touchpoints, which are error-prone, the quality increases. Likewise, because the system can scale up and down for demand, it is more efficient to run and costs less.

### Continuous Delivery
Cloud-native systems leverage IAC (infrastructure as code) to fully define the infrastructure. This means that deployment can target a dynamically created environment and that software can be automatically deployed to a new environment as it is created. Humans again are eliminated from the process of deployment increasing quality.

### DevOps
Cloud-native systems utilize DevOps. DevOps is a combination of automation, processes, and tools that increase automation, collaboration, and operational efficiency. Using Python for DevOps is a common way this automation is achieved.

### Agility
The agility of developing solutions improves. The cloud speeds up development time and increases quality through the use of IaC (Infrastructure as Code) and Continuous Delivery.

### Composable
Cloud-Native solutions are highly composable. The service design is one of integration. At the minimum, each service has an Application Programming Interface (API) that is consistent and discoverable. Other traits include well-defined behaviors for registration, discovery, and request management.

## Pros
- Ability to leverage near infinite resources of the cloud: Compute, Disk I/O, Storage, and Memory.
- No up-front costs and resources can be metered to meet demand like an electric or water utility.
- Applications are able to “go global” immediately with no extra investment.
- Increased reliability is increased as many cloud services are themselves highly available. A good example is Amazon S3 which has nine nine’s availability or is 99.999999999% reliable.
- Security is improved by consolidating to a centralized security model where there is a shared security partnership with the cloud vendor. They take care of portions of security such as access to the physical data center.
- The speed applications can be developed and tested are dramatically improved. With concepts like IAC (Infrastructure as Code), complete replicas of a production environment can be provisioned, tested, and then destroyed. This leads to increased quality of software and speed in which software can be developed.

## Cons
- Risk of creating systems that rely on a specific cloud vendor.
- The cost involved in migrating an application to a different architecture.
- A current organization may need to hire a new workforce trained to use the cloud or retrain their workforce.

## What is Fault-Tolerance?
Fault Tolerance - the property that enables a system to continue operating properly in the event of the failure of one or more of its components.

An example is a typical car, which is designed so it will continue to be drivable if one of the tires is punctured or damaged.
In computer systems, a fault-tolerant design enables a system to continue its intended operation, possibly at a reduced level, rather than failing completely, when some part of the system fails.
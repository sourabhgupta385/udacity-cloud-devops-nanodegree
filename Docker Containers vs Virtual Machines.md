## Why Docker Containers vs Virtual Machines?
What is the difference between a container and a virtual machine? Here is a breakdown:

- **Size:** Containers are much smaller than Virtual Machines (VM) and run as isolated processes versus virtualized hardware. VMs can be GBs while containers can be MBs.
- **Speed**: Virtual Machines can be slow to boot and take minutes to launch. A container can spawn much more quickly typically in seconds.
- **Composability**: Containers are designed to be programmatically built and are defined as source code in an Infrastructure as Code project (IaC). Virtual Machines are often replicas of a manually built system. Containers make IaC workflows possible because they are defined as a file and checked into source control alongside the project’s source code.
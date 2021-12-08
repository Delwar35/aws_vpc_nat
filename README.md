# AWS Networking
## VPC
### 2 Tier Architecture Deployment

**AWS Networking**
- IP address
> An IP address (Internet Protocol address) is a label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: network interface identification and location addressing.

- CDIR block
> CIDR block a method for allocating IP addresses and IP routing in the VPC. The IP can be IPv4 or IPv6 format.

> When you create a VPC, you assign it an IPv4/IPv6 CIDR block (a range of private and public IPv4/ipv6 addresses), or both (dual-stack). Private IPv4/IPv6 addresses are not reachable over the internet while public addresses are. To connect to your instance over the internet, or to enable communication between your instances and other AWS services that have public endpoints, you can assign a public IPv4/IPv6 address to your instance.

- IPV4 and IPV6
> IPv4 is a protocol for use on packet-switched Link Layer networks (e.g. Ethernet).IPv4 provides an addressing capability of approximately 4.3 billion addresses.

> IPv6 is more advanced and has better features compared to IPv4. It has the capability to provide more addresses the IPv6. It is replacing IPv4 to accommodate the growing number of networks worldwide and help solve the IP address exhaustion problem.

> One of the differences between IPv4 and IPv6 is the appearance of the IP addresses. IPv4 uses four 1 byte (8-bits) decimal numbers (range 0-255), separated by a dot (i.e. 192.168.1.1), while IPv6 uses hexadecimal numbers that are separated by colons (i.e. fe80::d4a8:6435:d2d8:d9f3b11).

**VPC and its resources**

![image](https://user-images.githubusercontent.com/94615905/145200431-e4544185-55b0-4cf5-913a-fdc5e904d4f6.png)

- Route table rules
> A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet or gateway is directed.

#### Route table rules for public subnet
##### AWS Example of public Route Table
![image](https://user-images.githubusercontent.com/94615905/145204885-7fa4966f-8a7c-4af7-bb4d-6e3de1f70065.png)

-- testing
-> test


#### Route table rules for private subnet

- SG rules
- Subnets cidr blocks
- Connectivity between app and db and app nat db

**2 Tier Architecture Deployment in our own VPC**

![image](https://user-images.githubusercontent.com/94615905/145200767-1f3b2c69-9d25-45de-aafc-4d77d9f448c8.png)

- should have all rules at all levels required




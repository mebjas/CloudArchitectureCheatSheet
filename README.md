# Cloud Architecture Cheat Sheet
Yet another repository of tips, tricks  &amp; (hopefully not obsolete) rule of thumbs for cloud architecture borrowed from internet without credits.

## Table of contents
 1. [What is cloud computing?](#What-is-cloud-computing?)
 2. [Performance](#Performance)
 3. [Scalability](#Scalability)
 4. [Availability](#Availability)

## What is cloud computing?
*Simply put, cloud computing is the delivery of computing services — servers, storage, databases, networking, software, analytics, intelligence and more-over the Internet ("the cloud") to offer faster innovation, flexible resources and economies of scale. You typically pay only for cloud services you use, helping lower your operating costs, run your infrastructure more efficiently and scale as your business needs change.* - Microsoft Azure

### Top Benefits of cloud computing
 - **Cost**: No more cost of hardware, software license, setting up, maintenance, electricity, network, internet. **That said, cloud services are not cheap either.** 
 - **Speed**: Most cloud services have self service portal, CLI tools to provision required resources in minutes. This eliminates time to setup infrastructure and softwares. Takes pressure off capacity planning.
 - **Global Scale**: Not everyone has the resources to have global datacenters yet it's really a good idea to have servers sitting close to customers for faster service. With cloud this is possible for everyone.
 - **Productivity**: No need to think of racking and stacking, focus on your application.
 - **Performance**: The quality of infrastructure held by popular cloud computing platforms are much better than many can setup. They generally host latest generation of hardware and software.
 - **Security**: Most of the tools and software have strengthened security in place.

### IaaS, PaaS, SaaS, DaaS, ZaaS ...
TBD

## Performance
TBD

## Scalability
TBD

## Availability
Simply put if you are building a cloud service, it's to serve certain ***customers***, certain ***something**. Availability refers to uptime of this ***something***. It's generally quantified in percentage of time you are able to provide this ***something*** to each customer. 90% availability means you were up for 9 out of 10 hours. 

** More Technical **
***Availability*** refers to the ability of the user community to obtain a service or good, access the system, whether to submit new work, update or alter existing work, or collect the results of previous work. If a user cannot access the system, it is - from the users’ point of view - ***unavailable***. Generally, the term ***downtime*** is used to refer to periods when a system is unavailable. 

#### Key Principles
Following three are important principles of reliability engineering which can help achieve high availability:
1. Elimination of single point of failure
2. Reliable Crossover
3. Detection of failure as they occur

### High Availability
High-availability is, ultimately, the holy grail of the cloud. It's generally quantified as number of **NINES**. For example: [99.9% availability](#99.9%-Availability---3-Nines) is generally called 3 9's of availability.

Here's how these transalates to uptime:

#### 99.9% Availability - 3 Nines
| Downtime Per year   | 8h 45min 57s  |
|---------------------|---------------|
| Downtime Per month  | 43m 49.7s     |
| Downtime Per week   | 10m 4.8s      |
| Downtime Per day    | 1m 26.4s      |

#### 99.99% Availability - 4 Nines
| Downtime Per year   | 52min 35.7s   |
|---------------------|---------------|
| Downtime Per month  | 4m 23s     |
| Downtime Per week   | 1m 5s      |
| Downtime Per day    | 8.6s      |

#### Types of failures
Some of the types of interruptions applications must handle is listed below: 

 - Hardware failures 
 - Deployment failures 
 - Increased load 
- Unexpected input errors 
- Credentials/Certificates expiration 
- Dependency Failures 
- Infrastructure failures like Power 

#### Availability vs Reliability - TBD
#### How to achieve high availability in cloud? - TDB
#### What availability is good availability? - TBD
#### Tradeoff between availability and cost - TBD
#### Tradeoff between availability and latency - TBD


## References
1. What is cloud computing - [Microsft Azure Documentation](https://azure.microsoft.com/en-in/overview/what-is-cloud-computing/)
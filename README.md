# AWS-Solution-Architect
Similar to the way architects design the structure of buildings, AWS Solutions Architects design cloud solutions. They help organizations meet business requirements by strategizing the most efficient system possible. They also collaborate with other AWS project teams to ensure the solution is implemented correctly.

## First up, let's understand a bit more about AWS
Before we get started with this task, let's give you some more context on AWS. <br>
AWS has myriad services for doing all kinds of things! While you don’t need to be familiar with them all, outlined below are a few that give you a sense of what type of services we provide and how they are billed. <br>
Please have a read through the services below and click next once you're done. It's likely that you'll need to use some of this information on the next part of this task - but you can easily navigate back and forth as required! 

### General Services

* __CodePipeline:__
This will build code and can deploy it to various AWS services. It is charged per pipeline. Can be used with Elastic Beanstalk for blue/green no-downtime deployments.

* __Elastic Load Balancing:__
Distributes traffic across application servers, such as EC2, Lambda or Fargate. Can use health checks to know which servers should service requests. Charges are based on the number of hours the load balancer runs and (at a high level) the amount of traffic it services. The actual charging rules can be quite complex.

* __RDS:__
Relational database hosting platform. Charged in the same way as EC2 (i.e. a virtual machine with a set amount of resources). Servers can be resized but must be restarted to do so.

* __Route 53:__
AWS' domain and DNS management.

* __S3:__
Store objects in the cloud. Charged based on the amount of data being stored, how it’s stored, and for retrieval.


### Application Executors

AWS provides a few ways of executing applications, from virtual machines, to container executors to function executors.

* __EC2:__
Scalable virtual servers. Charged based on resources of the virtual servers (RAM, CPU, storage), per hour. Servers can change their resource allocation but must be restarted to apply them.

* __Fargate:__
Run containerized applications (e.g., Docker images). Charges are based on the resources assigned to the container (RAM, CPU, etc.) and how long it runs for. Very scalable but can require manual orchestration.

* __Lambda:__
An application is uploaded to Lambda and only executed when triggered, for example, on HTTP request or via S3. For example, a Lambda instance would run to just service a single HTTP request. Charging is based on the amount of memory the Lambda uses and how long it runs for, plus the number of requests. Sometimes data transfers can also be charged depending on which region(s) a Lambda is fetching data from. Highly scalable up and down. Not suited for serving static content.

* __Lightsail:__
Virtual machines, like EC2 but simpler to set up. Charges are based on the resources of the Lightsail virtual machine. Virtual machines' resources can’t be changed, instead the machines must be cloned to a new instance and restarted. 

* __Elastic Beanstalk:__
Ties together EC2, RDS and Elastic Load Balancing with simple configuration and deployment. Its primary advantage is how it can facilitate the autoscaling of EC2 instances. Billing is based on a combination of the EC2, RDS and ELB that you use. Deployment is made easy with CLI tools, and we can use rolling deployments so there is no downtime. It has support for several languages including Python, NodeJS, Java and Go.

### Availability Zones

For extra redundancy, services can be deployed across multiple availability zones (AZ). This means that requests can fall over from one AZ to another in the case of infrastructure failure. In general, the cost of a service is multiplied by the number of availability zones it’s in.

You should be able to tell the customer why you have chosen Elastic Beanstalk and what components it contains, and the purpose of these. The AWS resource pages for each service contain descriptions of how they are charged.

* CodePipeline
* Elastic Load Balancing
* RDS
* Route 53
* S3
* Elastic Beanstalk

The concrete pricing differs in each region, however, the method of price calculation is the same. For example, an EC2 instance in Region A may cost more than the same instance in Region B, however, both are billed at an hourly rate. The AWS pricing calculator at https://calculator.aws/ can also give some guidance.

## AWS APAC Solutions Architecture virtual experience program on Forage - March 2024

 * Designed and simple and scalable hosting architecture based on Elastic
   Beanstalk for a client experiencing significant growth and slow response
   times.
 * Described my proposed architecture in plain language ensuring my client
   understood how it works and how costs will be calculated for it.

## “Why are you interested in this role?”

I recently participated in the AWS virtual job simulation on the Forage
platform, and it was incredibly useful to understand what it might be like to be
a Solutions Architect on the AWS team. I really enjoyed creating an architecture
diagram and drafting a plain language email to explain how it works and how
costs would be calculated to my client. 
The realistic context helped me to understand how critical the relationship can
be between the CTO of an early stage company and their Solutions Architect at
AWS. I also learned how being thoughtful and considered as a Solutions Architect
can significantly reduce the stress faced by clients. 
Through this program I realized that I really enjoy working on designing hosting
architecture and would love to apply what I've learned as a Solutions Architect
at AWS.

## Skills

* ARCHITECTURE DIAGRAM
* AWS PRICING
* TECHNICAL COMMUNICATION

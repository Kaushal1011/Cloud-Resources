# Web Development Engineer

## DevOps

DevOps is the combination of cultural philosophies, practices, and tools that increases an organization’s ability to deliver applications and services at high velocity: evolving and improving products at a faster pace than organizations using traditional software development and infrastructure management processes. This speed enables organizations to better serve their customers and compete more effectively in the market.

- Continuous Integration: is a DevOps software development practice where developers regularly merge their code changes into a central repository, after which automated builds and tests are run
- Continuos Delivery: is a DevOps software development practice where code changes are automatically built, tested, and prepared for a release to production.

## Blue/Green DevOps

A blue/green deployment is a change management strategy for releasing software code. Blue/green deployments, which may also be referred to as A/B deployments require two identical hardware environments that are configured exactly the same way. While one environment is active and serving end users, the other environment remains idle.

Blue/green deployments are often used for consumer-facing applications and applications with critical uptime requirements. New code is released to the inactive environment, where it is thoroughly tested. Once the code has been vetted, the team makes the idle environment active, typically by adjusting a router configuration to redirect application program traffic. The process reverses when the next software iteration is ready for release.

-[Check Out on Aws](https://aws-quickstart.s3.amazonaws.com/quickstart-codepipeline-bluegreen-deployment/doc/blue-green-deployments-to-aws-elastic-beanstalk-on-the-aws-cloud.pdf)

## Infrastructure as code

Using AWS CloudFormation you can write a description of the resources that you want to create on your AWS account, and then ask AWS CloudFormation to make this description into reality.

Benefits of Infrastructure as code

- Visibility: An infrastructure as code template serves as a very clear reference of what resources are on your account, and what their settings are. You don’t have to navigate to the web console to check the parameters.
- Stability: If you accidentally change the wrong setting or delete the wrong resource in the web console you can break things. Infrastructure as code helps solve this, especially when it is combined with version control, such as Git.
- Scalability: With infrastructure as code you can write it once and then reuse it many times. This means that one well written template can be used as the basis for multiple services, in multiple regions around the world, making it much easier to horizontally scale.
- Security: Once again infrastructure as code gives you a unified template for how to deploy your architecture. If you create one well secured architecture you can reuse it multiple times, and know that each deployed version is following the same settings.
- Transactional: CloudFormation not only creates resources on your AWS account but also waits for them to stabilize while they start. It verifies that provisioning was successful, and if there is a failure it can gracefully roll the infrastructure back to a past known good state.

## AWS CLI

The AWS Command Line Interface (CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts.

The AWS CLI introduces a new set of simple file commands for efficient file transfers to and from Amazon S3.

- [AWS CLI AND CLI TOOLS](https://aws.amazon.com/tools/)

## Web Dev

- [Static Website](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)
- [S3](https://docs.aws.amazon.com/s3/index.html)
- [Web Hosting](https://d1.awsstatic.com/whitepapers/aws-web-hosting-best-practices.pdf)
- [And Much More](https://awseducate.instructure.com/courses/193/pages/software-development-web-development?module_item_id=4629)

## Mobile Dev

- [Aws Amplify](https://aws.amazon.com/amplify/)
- [Aws Mobile](https://aws-amplify.github.io/docs/)
- [Aws Mobile Hub](https://aws.amazon.com/blogs/aws/aws-mobile-hub-build-test-and-monitor-mobile-applications/)

## Game Dev

- [Aws Mobile For Startups and Gaming](https://awseducate.instructure.com/courses/193/pages/software-development-mobile-for-startups-and-gaming?module_item_id=4631)

## Databases

### Data Structures

- [Basics](https://medium.com/swlh/introduction-to-data-structures-9134b7d064a6)
- [Edx](https://www.edx.org/course/data-structures-fundamentals)
- [Cloud Oriented DS](https://www.coursera.org/lecture/cloud-computing/orientation-towards-cloud-computing-concepts-some-basic-computer-science-9vZYG)

___Very Important Reading___

- [Important Reading](https://www.allthingsdistributed.com/2018/06/purpose-built-databases-in-aws.html)

### Non-Relational

- [MongoDB on AWS](https://docs.aws.amazon.com/quickstart/latest/mongodb/welcome.html)
- Read More on NoSQL Databases.

### Relational

- [Link](https://awseducate.instructure.com/courses/193/pages/databases-relational?module_item_id=4634)

## Network

Topics related to Networking:

- Architecture and Troubleshooting
- Infrastructure Provisioning
- Directory Services

### Architecture

Network Architecture is the complete framework of an organization's computer network. The diagram of the network architecture provides a full picture of the established network with detailed view of all the resources accessible. It includes hardware components used for communication, cabling and device types, network layout and topologies, physical and wireless connections, implemented areas and future plans. In addition, the software rules and protocols also constitute to the network architecture. This architecture is always designed by a network manager/administrator with coordination of network engineers and other design engineers.

Cloud computing architecture refers to the components and subcomponents required for cloud computing. These components typically consist of a front end platform (fat client, thin client, mobile device), back end platforms (servers, storage), a cloud based delivery, and a network (Internet, Intranet, Intercloud).

#### Front End Platform

Front-end is the side that is visible to the client, customer, or user. Front-end pieces include the user interface, and the client’s computer system or network that is used for accessing the cloud system.

#### Back End Platform

The back-end pieces are on the side used by the service provider. These include various servers, computers, data storage systems, virtual machines, and programs that together constitute the cloud of computing services. The back-end side also is responsible for providing security mechanisms, traffic control and protocols that connect networked computers for communication.

#### Cloud Based Platform

Cloud computing services are everywhere these days. For example, if you use QuickBooks for your accounting, or Expedia to schedule your travel, or Netflix to watch you favorite series, you’re a cloud computing user. These are all examples of subscriptions a company or individual can purchase that enable them to use the software, typically known as Software-as-a-Service, or SaaS.

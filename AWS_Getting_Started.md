# Getting Started with AWS - [Reference](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-intro.html)

## Regions and Availability Zones

* Amazon has data centers in different **Regions** like North America, Europe & Asia

	ap-northeast-1	Asia Pacific Tokyo
	ap-northeast-2	Asia Pacific Seoul
	ap-southeast-1	Asia Pacific Singapore
	ap-southeast-2	Asia Pacific Sydney
	eu-central-1	Europe Frankfurt
	eu-west-1	Europe Ireland
	us-east-1	US East N.Virginia
	us-west-1	US West N.California
	us-west-2	US West Oregon
	sa-east-1	South America (Sao Paulo)
	
* Each **Region** contains multiple distinct locations called **Availabilty Zones**

	AZ are engineered to be isolated from failures in other AZ
	Resources are placed multiple AZ to protect from failure of single location
	Provides inexpensive, low-latency network connectivity to other AZ in sames Region
	
## Security

* Security credentials of users and their fine grained access to AWS resources are managed using **IAM**
* Data at rest is encrypted and their access is provided based on ACL permissions
* **VPC** is virtual network that is logically isolated from other networks in the AWS cloud
* **Security Group** acts a firewall to control the inbound and outbound traffic for Virtual servers
* **Key Pairs** are used to encrypt login information. It is presented during the login to virtual server to decrypt login information

## Product Categories

* Compute and Networking Services
* Storage and Content Delivery
* Security and Identity Services
* Database Services
* Application Services
* Enterprise Services
* Developer Tools
* Management Tools
* Analytics Services
* Gaming
* IOT
* Mobile

## Compute and Networking Services for AWS

* Provision Virtual Servers
* Set up firewall
* Configure internet access
* Allocate and route IP address
* Scale your infrastruture

	Amazon EC2 - Provides virtual servers in the AWS cloud.
	
	Amazon VPC - Provides an isolated virtual network for your virtual servers.
	
	Elastic Load Balancing - Distributes network traffic across your set of virtual servers.
	
	Auto Scaling - Automatically scales your set of virtual servers based on changes in demand.
	
	Amazon Route 53 - Routes traffic to your domain name to a resource, such as a virtual server or a load balancer.
	
	AWS Lambda - Runs your code on virtual servers from Amazon EC2 in response to events.
	
	Amazon ECS - Provides Docker containers on virtual servers from Amazon EC2.
	
## Storage and Content Delivery Services for AWS

	Amazon S3 - Scalable storage in the AWS cloud.
	
	CloudFront - A global content delivery network (CDN).
	
	Amazon EBS - Network attached storage volumes for your virtual servers.
	
	Amazon Glacier - Low-cost archival storage.


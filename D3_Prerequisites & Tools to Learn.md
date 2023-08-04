##########################
  **Topics for Discussion**
##########################

Let's Revise Day 02 Quickly

Overview of Complete DevOps RoadMaps (MindMap)

Get Started with DevOps Prerequisite and Tools and Tech (MindMap)

Realtime Use cases Of Python (4 Scenarios Discussed)

What Topics to Cover in Networking Concepts (MindMap)?

What is Subnets (Realtime Use cases)?

What is Public & Private Networks?

What is CIDR Notations and How to Identify Network & Host Bits?

Static Vs Dynamic IP (Realtime Use cases Example)

What is #firewall?

What is Proxy?

Difference between Public & private DNS?

What is VPN?

What is Protocols? and What are the Port numbers of Some Important Protocols

What is Security and How it Helps?

What is reverse Proxy and How it Works?

What is Forward Proxy and How it helps?

Which Cloud Service i should Choose?

Operating Systems and Important Topics of OS 

What is Important DevOps That is mandatory to Know? (Various Tools with Realtime use cases and Scenarios)

#############################################################################################




Let's Revise Day 01 Quickly 
**Overview of Complete DevOps RoadMaps (MindMap)**
For Beginners and Experienced 

1)	DevOps Roadmap
2)	Prerequisites 
3)	Tools & Technologies

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/e86cbf28-1e44-4956-a20d-a56be2dcf9d2)

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/7c00d393-ee0e-474a-93de-7ccdb506ed5c)

**Real-time Use cases of Python:**

Scenario 1:  Shutdown the DEV servers on Weekends

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/9e63770a-a3f2-4524-bb1f-7e103d0ae40e)

Scenario 2: Cleanup the servers to free spaces

At schedule time python scripts executes and cleanup the VM and the applications deployed onto those servers runs smoother.

Scenario 3: Attach disks to EC2 instance

You have set CloudWatch alarm if storage >80% it will try to perform cleanup activities, but when its is above that threshold even after cleanup, it should attach the disk to the VM

Scenario 4: Automate day-to-day GitHub tasks

These are just examples and Logic building is very much required here.

**Basics of Networking are enough**

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/ffbef5e7-aad8-4a3b-ba25-4db951709f95)

**Subnet:** Subnet is something where you split your large network into a group of smaller inter-connected network which will help you to minimize the traffic.

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/f8ca114f-22db-4e28-a0d7-5b64ad0d5e75)

**Public & Private Network:**


 Private network is something where the services are controlled by single organization.

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/33c530b9-8754-40a4-bbe6-7b33875574de)

Public network is something where the services are commonly accessible to the customers want to use the similar service. Ex, Amazon, Flipkart. 

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/71733766-c159-4e74-951a-75e0069cfa5c)


**CIDR Notations:**

CIDR notation is something; these are amount of bits allocated to the network 

Subnets are subdivisions of VPC’s

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/f31136bb-a013-4411-b817-5e82869047f0)

How do we calculate the CIDR?

Ip/24 **-->** CIDR

The complete bits are 32 where 24 bits are allocated to network 8 bits are allocated to host

8 bits **-->** ![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/014e182e-6c71-4c25-8073-d06565e5ca4e)
no of ip’s are going to be allocated to the hosts (many servers)

**Static Vs Dynamic IP:**

When you create an EC2 instance you get an Dynamic IP (Public IP). Whenever you reboot the server, ip gets changed, which is ok for DEV environment. But for Production it requires Static IP (IP should not get changed)

**Firewalls:**

Firewall is kind of network security device, which does monitors and filters incoming and outgoing traffic


![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/06aaaa5b-b50f-4e93-83f8-7a09fee6b2cb)

All this happens based on Organizations previously obtained Security Policies.

**Proxy:**

We can consider this as a router/system, and what it does is provide a gateway between your users and the internet.  Apart from that it helps prevent cyber attackers entering private networks.


![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/012c7d4b-324e-40b4-977d-7358fb10ded9)

**Public & Private DNS:**

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/71d8486f-40b6-437b-9edb-d79eca4e4006)


**VPN:**

What is VPN?  It enables private connection between two machines or network over a shared public network.

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/6f8bba09-0a3e-44b9-b264-8a83d5e0ca0d)

You are able to access public services like Amazon, Flipkart etc using or by connecting to a private network securely. 

Ex: you play pubg using VPN

**Protocols:**
It is a bit important to be aware of.

Protocol is something that provides a medium and set of rules which allows establishing connection between different devices for exchange of data and other services.

**Security**

Security is something it is a collection of procedures and technologies which are designed to address external and internal threats to business security.


![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/c131fe05-86b1-4fae-8163-33e2435b1b70)

**Reverse Proxy**

Reverse proxy?  Is basically sits behind the firewall in the private network. 

Directs client request to appropriate backend server when requesting for something.

![image](https://github.com/DevenderMusukula/DevOps-Training-Documentations/assets/119439237/b3077207-07da-4df8-be57-723cfe66e59a)

**Forward Proxy?**  This is also known as most common form.

Passes requests from an isolated private network to internet through firewall.

**Cloud:**

Aws

Azure

GCP 

**Operating Systems: **

Linux/Unix

I/O management

Virtualization concepts like Hypervisor.

File Systems

Threads & Process Management. 

Program under execution is called as process. And thread is segment of process i.e; it is part of the process, we can say as set of tasks in a process and that set of tasks runs independently.

By this we are done with Pre-requisites, lets look into Tools & Technologies.

**Which Cloud Service I should Choose?**

Tools & Technologies

VCS **-->** **Git/GitHub**/SVN

Build Tools **-->** **Maven** / Gradle / etc….

Configuration Management **-->** **Ansible** / Chef / Puppet / etc…

Infrastructure As A Code **->** **Terraform** /AWS Cloud Formation / Azure Resource Manager

**Why IAAC?**

Suppose you joined an organization, and you were asked to create 100 servers where 50 are to be with Linux image and 50 servers are with Ubuntu.

Are you going to AWS console and creating all of these?

No, this is not good way to do it. So in this case IAAC came to help.

You write the Terraform code in **.tf** files mentioning the requirements and you will be variable-ising and you can create number of servers just by executing the **.tf** file 📢

After execution, you will get **tfstate** files as well, which consists the info of whatever you have created and you have to maintain the **tfstate** file and we store it in S3 bucket.

You have configured 100 servers and you have your **tfstate** file, next day you missed adding one more server (to add one more server),  if you miss this **tfstate** file, it will again try to create the 100 servers  and it will fail.
So that is why your tfstate  file is there to compare your current configuration and the existing configuration and finds that there are already 100 servers created and it only creates the one newly added server.
This is how Terraform helps you a lot 👍

**Containerization Tools:**

**-->** Docker

You have gone through in Day1 session how docker resolved the issues and dependencies between QA team and different teams using this docker concept.

**Orchestration Tool:**

Kubernetes (Big and vast topic, we just have to know atleast basic of containerization and orchestration )
**-->** Docker Swarm (Kubernetes of Docker)

**-->** OpenShift

**Monitoring Tools:**

**-->** Prometheus

**-->** Grafana

**-->** Splunk

**-->** Dynatrace

**-->** Datadog

This is all about the Complete DevOps Roadmap for a beginner or experienced.

We have seen

1)	Prerequisites to be followed
2)	Tools & Technologies (Much important to become DevOps engineer)

We will be having separate sessions on these tools.

When you think about prerequisites, all those are mandatory and really required?

To say, if we are a beginner, we don’t need to go in-depth like networking concepts/ Security aspects but you should know about Linux, Shell Scripting, and Groovy Scripting.  And n/w concepts means not all but suggest learning Subnets, CIDR notations, Static IP’s, Proxy, and VPN.  This might not be really mandatory but if you have to ease your understanding of DevOps implementations and Phases and also ease your work.

**Create and Connect to EC2 Instance**

**-->** How to create our First EC2 Instance & High Level explanation of each & every step 

**-->** How to Pass scripts to Install on Server while creating?

**-->** Connect Ubuntu EC2 Instance using CloudShell

**-->** How to Connect to Ubuntu Ec2 On Windows Os?

**-->** How to Connect to Ubuntu EC2 Using MobaXterm on Windows Os?

**-->** How to Connect to Windows EC2 on Windows Os?

**-->** Quick revision of instance creation

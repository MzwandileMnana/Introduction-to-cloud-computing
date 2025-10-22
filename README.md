# Introduction-to-cloud-computing
Notes for introduction to cloud computing course

There are three primary cloud service models, often summarized as:

1. IaaS – Infrastructure as a Service
✅ Functionality:

Provides virtualized computing resources over the internet such as:

Virtual machines (VMs)

Storage

Networks

Load balancers

Firewalls

🔧 Use Case:

Developers or IT admins want to build and manage their own applications without buying physical hardware.

🧩 Examples:

Amazon Web Services (AWS) EC2

Microsoft Azure Virtual Machines

Google Compute Engine

📌 Key Features:

Full control over the OS and applications

Scalable resources on demand

Pay-as-you-go pricing

2. PaaS – Platform as a Service
✅ Functionality:

Provides a ready-to-use platform for developing, testing, and deploying applications without worrying about infrastructure management.

🔧 Use Case:

Developers want to focus only on writing code without managing the underlying OS, storage, or servers.

🧩 Examples:

Google App Engine

Microsoft Azure App Services

Heroku

📌 Key Features:

Managed runtime environment

Built-in tools for development and deployment

Faster time to market

3. SaaS – Software as a Service
✅ Functionality:

Delivers fully functional software applications over the internet, typically through a web browser.

🔧 Use Case:

End-users need ready-to-use software without installation or maintenance.

🧩 Examples:

Google Workspace (Docs, Gmail)

Microsoft 365

Salesforce

Dropbox

📌 Key Features:

Accessible from any device with internet

No software installation required

Maintenance and updates handled by provider

Summary Table:
Model	Managed by Provider	Managed by You	Typical Users
IaaS	Hardware	OS, Apps	System admins, DevOps
PaaS	Hardware, OS, Middleware	Apps	Developers
SaaS	Everything	Just use it	End users (business users)


#A virtual machine (VM) is a software-based emulation of a physical computer. It runs an operating system (OS) and applications just like a physical computer, but it's hosted on a physical machine called the host and managed by a hypervisor.

Key Concepts:
1. Host vs. Guest

Host: The physical machine and its OS.

Guest: The virtual machine and its OS running on the host.

2. Hypervisor (Virtual Machine Monitor)

The software that creates and manages virtual machines. Two types:

Type 1 (Bare-metal): Runs directly on hardware (e.g., VMware ESXi, Microsoft Hyper-V).

Type 2 (Hosted): Runs on top of an OS (e.g., VirtualBox, VMware Workstation).

3. Isolation

Each VM is isolated from others and from the host, which means:

VMs can run different operating systems.

Crashes or malware in one VM don't affect others.

What Can You Do with a VM?

Run multiple OSes (e.g., Linux on a Windows machine).

Test software safely in a sandbox.

Run legacy applications on older operating systems.

Create reproducible development environments.

Example

You’re using a Mac, but need to run Windows software:

Install VirtualBox (Type 2 hypervisor).

Create a Windows VM.

Install and run Windows apps inside that VM.

In this video, we will discuss the Infrastructure-as-a-Service model in more detail. Infrastructure-as-a-Service, commonly referred to as “IaaS,” – or simply “eye-es” - is a form of cloud computing that delivers fundamental compute, network, and storage resources to consumers on-demand, over the internet, on a pay-as-you-go basis. The cloud provider hosts the infrastructure components traditionally present in an on-premises data center as well as the virtualization or hypervisor layer. In an IaaS Cloud environment, customers can create or provision virtual machines (or VMs) in their choice of Region and Zone available from the Cloud Provider. These VMs typically come pre-installed the customer’s choice of operating system. The customers can then deploy middleware, install applications, and run workloads on these VMs. They can also and create storage for their workloads and backups. 
Cloud providers often provide customers the ability to track and monitor the performance and usage of their cloud services and manage disaster recovery. Let’s look at the key components of cloud infrastructure: Physical data centers: IaaS providers manage large data centers that contain the physical machines required to power the various layers of abstraction on top of them. In most IaaS models, end users do not interact directly with the physical infrastructure but experience it as a service provided to them. Compute: IaaS providers manage the hypervisors and end-users programmatically provision virtual instances with desired amounts of compute, memory, and storage resources. Cloud compute typically comes with supporting services like auto scaling and load balancing that provide scalability and high performance. Network: Users get access to networking resources on the cloud through virtualization or programmatically, through APIs. Storage: There are three types of cloud data storage: object, file, and block storage. 
Object storage is the most common mode of storage in the cloud, given that it is highly distributed and resilient. IaaS supports a wide array of use cases. We’ll look at some typical use cases here. Organizations today are using cloud infrastructure services to enable their teams to set up test and development environments faster, helping create new applications more quickly. By abstracting the low-level components, cloud infrastructure is helping developers focus more on business logic than infrastructure management. Business continuity and disaster recovery require a significant amount of technology and staff investments. IaaS is helping organizations reduce this cost and make applications and data accessible as usual during a disaster or outage. 
Organizations are using cloud infrastructure to deploy their web applications faster and also scale infrastructure up and down as demand fluctuates. Organizations are leveraging the high-performance computing capabilities of cloud infrastructure to solve complex problems involving millions of variables and calculations such as climate and weather predictions and financial modeling. Mining massive data sets to locate valuable patterns, trends, and associations requires a huge amount of processing power. Cloud infrastructure not only provides the required high-performance computing but also makes it economically viable. While there are some concerns regarding the lack of transparency in the cloud infrastructure’s configuration and management and dependency on a third-party for workload availability and performance, Infrastructure-as-a-Service is the fastest growing cloud model today. In the next video, we will look at Platform-as-a-Service model, its features, benefits, and some use cases

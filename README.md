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


A virtual machine (VM) is a software-based emulation of a physical computer. It runs an operating system (OS) and applications just like a physical computer, but it's hosted on a physical machine called the host and managed by a hypervisor.

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

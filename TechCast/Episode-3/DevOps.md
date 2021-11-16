# TechCast Episode-3

Greetings, welcome to the DevOps-Hactober documentation. We have put together a small yet not so small info pamplet for you to get started with DevOps. Let's get cracking!

## What is DevOps?

The name DevOps is combination of the words 'development' and 'operations'. DevOps isn't a software or just a tool, rather it is a set of 'practices', 'tools', and 'cultural philosophy' that automates and integrates softare developments and IT teams.

Microsoft defines DevOps as: "DevOps enables formerly siloed roles—development, IT operations, quality engineering and security—to coordinate and collaborate to produce better, more reliable products. By adopting a DevOps culture along with DevOps practices and tools, teams gain the ability to better respond to customer needs, increase confidence in the applications they build and achieve business goals faster."

  
## How does DevOps work?

A DevOps team includes developers and IT operations working collaboratively throughout the product lifecycle, in order to increase the speed and quality of software deployment. It’s a new way of working, a cultural shift, that has significant implications for teams and the organizations they work for.

Under a DevOps model, development and operations teams are no longer “siloed.” Sometimes, these two teams merge into a single team where the engineers work across the entire application lifecycle — from development and test to deployment and operations — and have a range of multidisciplinary skills.

DevOps teams use tools to automate and accelerate processes, which helps to increase reliability. A DevOps toolchain helps teams tackle important DevOps fundamentals including continuous integration, continuous delivery, automation, and collaboration.

DevOps values are sometimes applied to teams other than development. When security teams adopt a DevOps approach, security is an active and integrated part of the development process. This is called DevSecOps.

  

## The DevOps lifecycle

Because of the continuous nature of DevOps, practitioners use the infinity loop to show how the phases of the DevOps lifecycle relate to each other. Despite appearing to flow sequentially, the loop symbolizes the need for constant collaboration and iterative improvement throughout the entire lifecycle.  
![](https://azurecomcdn.azureedge.net/cvt-a61762d91bc238e08c3e3c971648841b9b4c6c30e806d7be1a4fe7066d59b79f/images/page/overview/devops/index/lifecycle.png)  
  

### **Plan**

DevOps teams should adopt agile practices to improve speed and quality. Agile is an iterative approach to project management and software development that helps teams break work into smaller pieces to deliver incremental value.

  

### **Develop**

The develop phase includes all aspects of coding—writing, testing, reviewing and the integration of code by team members—as well as building that code into build artifacts that can be deployed into various environments. DevOps teams seek to innovate rapidly without sacrificing quality, stability and productivity. To do that, they use highly productive tools, automate mundane and manual steps and iterate in small increments through automated testing and continuous integration.

  

### **Deliver**

Delivery is the process of deploying applications into production environments in a consistent and reliable way. The deliver phase also includes deploying and configuring the fully governed foundational infrastructure that makes up those environments. In the deliver phase, teams define a release management process with clear manual approval stages. They also set automated gates that move applications between stages until they’re made available to customers. Automating these processes makes them scalable, repeatable, controlled. This way, teams who practice DevOps can deliver frequently with ease, confidence and peace of mind.

  

### **Operate**

The operate phase involves maintaining, monitoring and troubleshooting applications in production environments. In adopting DevOps practices, teams work to ensure system reliability, high availability and aim for zero downtime while reinforcing security and governance. DevOps teams seek to identify issues before they affect the customer experience and mitigate issues quickly when they do occur. Maintaining this vigilance requires rich telemetry, actionable alerting and full visibility into applications and the underlying system.

  
  

## Advantages of DevOps

### **Speed**

Teams that practice DevOps release deliverables more frequently, with higher quality and stability. In fact, the DORA 2019 State of DevOps report found that elite teams deploy 208 times more frequently and 106 times faster than low-performing teams. Continuous delivery allows teams to build, test, and deliver software with automated tools.

### **Improved collaboration**

The foundation of DevOps is a culture of collaboration between developers and operations teams, who share responsibilities and combine work. This makes teams more efficient and saves time related to work handoffs and creating code that is designed for the environment where it runs.

### **Rapid deployment**

By increasing the frequency and velocity of releases, DevOps teams improve products rapidly. A competitive advantage can be gained by quickly releasing new features and repairing bugs.

### **Quality and reliability**

Practices like continuous integration and continuous delivery ensure changes are functional and safe, which improves the quality of a software product. Monitoring helps teams keep informed of performance in real-time.

### **Security**

By integrating security into a continuous integration, continuous delivery, and continuous deployment pipeline, DevSecOps is an active, integrated part of the development process. Security is built into the product by integrating active security audits and security testing into agile development and DevOps workflows.  
  

Now, a question that arises is how does a company go about establishing DevOps in it's environment?. To help in shifting to DevOps various technologies have been developed. A few of them are mentioned below:

#### **Atlas**

- Atlas was the first commercial product released by HashiCorp, provider of open-source tools that enable the efficient deployment of software-defined applications and data centers. Atlas provides visibility into the infrastructure, including virtual machines, containers and servers, in addition to service discovery and configuration management. Building on the popular open-source projects of HashiCorp such as Terraform, Consul, Serf, Packer and Vagrant, the closed-source proprietary Atlas enables DevOps across different cloud services, which include OpenStack, Azure, Google Compute Engine and AWS, and provides a dashboard for maintaining, deploying and developing applications. Many engineers are shifting to Atlas today for their organizations’ customer engagement platforms. Atlas brings it in one place and enables the companies to handle end-to-end starting from configuration management to container deployments across various cloud environments. Every open-source tool is fine alone, but the capability to handle and orchestrate them as a whole is extremely powerful.

#### **Chef**

- Chef is a cloud infrastructure and systems framework that automates the management, deploying and building of the infrastructure via repeatable, short scripts known as “recipes.” But the actual strength of Chef lies in its utilization of the pluggable configuration modules(also known as cookbooks), about 2,000 of which are available through Chef community. Facebook, the high-profile user of Chef, recently open-sourced few of its own Chef cookbooks, which include its Grocery Delivery and Taste Tester testing framework, which watches a source code repository such as Git and keeps the local Chef server in sync.The complex tasks are automated by Chef that are otherwise resource- and time-intensive. But, more importantly, Chef allows users to focus their efforts on improving and innovating the quality of their services. It also opens the door to more efficiency and collaboration across the organization.

#### **Docker**

- Through its containerization technology, Docker brings portability to the applications wherein the applications run in self-contained units that can be moved across the platforms. It consists of Docker Hub, a cloud service for workflow automation and application-sharing and Docker Engine, which is a lightweight packaging and runtime tool. Docker has revolutionized the containerization of applications enabling DevOps to package any kind of application in a lightweight environment. The packaging is done in a way as easy as installing a mobile app. Docker is considered as the most popular DevOps tool. By using docker, the developers can containerize their apps and can run them anywhere. Built on top of Linux containers, docker is a powerful ecosystem where DevOps can use many apps (available on Docker Hub) to the maximum advantage.

#### **Splunk**

- Splunk is used for detecting and fixing issues across the life cycle of an application in real time. It allows the developers to see data from the production environments, eliminating the need to access production machines. Splunk enables DevOps processes including continuous integration and deployment.

#### **IaaS**

- Infrastructure as a service (IaaS) is a cloud computing offering in which a vendor provides users access to computing resources such as storage, networking, and servers. Organizations use their own platforms and applications within a service provider's infrastructure.IaaS allows multiple users to share the same physical infrastructure. Iaas allows IT users to access resources over the internet. IaaS providers provide services based on the pay-as-per-use basis. The users are required to pay for what they have used. Notable examples of IaaS are, Amazon Web Services(AWS), Google Compute Engine(GCE), and Microsoft Azure

#### **Grafana**

- Grafana is an open source solution for running data analytics, pulling up metrics that make sense of the massive amount of data & to monitor our apps with the help of cool customizable dashboards. The tool helps us study, analyse & monitor data over a period of time, technically called time series analytics.Companies use Grafana to monitor their infrastructure and log analytics, predominantly to improve their operational efficiency. Dashboards make tracking users and events easy because it automates the collection, management and viewing of data.

  
  

## GitHub Workflow
  
GitHub Actions makes it easy to automate all your software workflows. After each push, it checks wether the code is up to the pre-set standards and updates it. In the event that the code doesn't match the standards it is formated to the pre-set standards. This is called Continous Integration, these tools help your team's quality standards by running tests every time you push a new commit. This allows organizations to make sure everyone is working on the same level and version of the application, meaning a change in one person's copy can be updated to everyone else in the organization with ease. This helps increase efficiency and also streamlines all the work. And once the changes have been approved/merged/pushed. We can deliver it right away. As a result, the changes are made public, and the website or application is updated. So, if the build fails, the update will not be rolled out until the problem is resolved. So it allows developers to work safely and quickly on any application they are working on. All the above mentioned tasks when done manually, take a lot of time and there is a high chance of errors creeping in.

Our very own OpenSource101 has implemented a sophisticated workflow for everyone on GitHub, for each commit there's a confirmation notifying the users about the changes

  
  

## DevOps Engineer

If you found all of this to be very intresting and quite the challenge, you might be wondering what are the skills required for a DevOps engineer. The following will cover all if not most of your queries

### Who is a DevOps engineer?

IT generalist, having a wide-ranging knowledge on both development and operations, including coding, infrastructure management, system administration, and DevOps toolchains. DevOps engineers should also possess interpersonal skills since they work across company silos to create a more collaborative environment.

  
### What skills should a DevOps engineer have?

The technical skills required of a DevOps engineer will vary depending on the team structure, technologies, and toolsets in use. Yet strong communication and collaboration skills are essential. It’s also important for a DevOps engineer to have a solid understanding of all the components of a delivery pipeline, and to know the pros and cons of available tools and services.

-   Communication and collaboration
-   System administration
-   Experience with DevOps tools
-   Configuration management
-   Continuous integration and continuous deployment
-   System architecture and provisioning
-   Collaborative management skills
-   Familiarity with coding and scripting

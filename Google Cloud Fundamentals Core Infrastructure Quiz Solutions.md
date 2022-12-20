GOOGLE CLOUD FUNDAMENTALS: CORE INFRASTRUCTURE QUIZ ANSWERS (TOPIC WISE) ::

# Topic 1:
## Quiz Questions
#### Q1. Why might a Google Cloud customer use resources in several zones within a region?
- [x] For improved fault tolerance
- [ ] For getting discounts on other zones
- [ ] For better performance
- [ ] For expanding services to customers in new areas

#### Q2. Who benefits the most from billing by the second for cloud resources, such as virtual machines?
- [ ] Customers who create virtual machines that run commercially licensed operating systems
- [x] Customers who create and run many virtual machines
- [ ] Customers who create many virtual machines and leave them running for monthsCustomers who create many virtual machines and leave them running for months
- [ ] Customers who create too few virtual machines to get discounts

#### Q3. Select two fundamental characteristics of cloud computing from this list.
- [x] Resources are available from anywhere over the network.
- [ ] Customers are required to commit to multi-year contracts.
- [x] Customers can scale their resource use up and down.
- [ ] Providers always dedicate physical resources to each customer.
- [ ] All resources are open source.

#### Q4. What cloud computing service provides raw compute, storage, and network resources that are organized similarly to physical data centers?
- [x] Infrastructure as a service
- [ ] Database as a service
- [ ] Platform as a service
- [ ] Software as a service

#### Q5. Which one of the following statements is true regarding the ability to scale cloud computing resources up and down?
- [ ] Only storage resources are elastic.
- [ ] Only CPU and memory resources are elastic.
- [x] CPU, memory, and storage resources are elastic.
- [ ] Cloud computing does not provide a way to scale resources.

#### Q6. What cloud computing service binds application code to libraries that give access to the infrastructure an application needs?
- [ ] Hybrid cloud
- [ ] Infrastructure as a service
- [ ] Virtualized data centers
- [ ] Software as a service
- [x] Platform as a service


# Topic 2: 
## Quiz Questions
#### Q1. Select the option that displays IAM roles from general to specific.
- [ ] Predefined roles, custom roles, basic roles
- [x] Basic roles, predefined roles, custom roles
- [ ] Custom roles, predefined roles, basic roles

#### Q2. Your company has two Google Cloud projects and you want them to share policies. What is the least error-prone way to set this up?
- [ ] Create shared resource policies on the common resources that are used in both projects.
- [ ] Define the new shared policy in the organization node.
- [ ] Duplicate all the policies from one project onto the other.
- [x] Place both projects into a folder, and define the policies on that folder.

#### Q3. Consider a single hierarchy of Google Cloud resources. Which of these situations is possible? (Choose 3 responses.)
- [x] There is an organization node, and there are no folders.
- [x] There is an organization node, and there is at least one folder.
- [ ] There are two or more organization nodes.
- [x] There is no organization node, and there are no folders.
- [ ] There is no organization node, but there is at least one folder.

#### Q4. How does the resource hierarchy control how IAM policies are inherited?
- [ ] IAM policies are only implemented at the project level; they cannot be amended by lower levels of the resource hierarchy.
- [ ] IAM policies that are implemented higher in the resource hierarchy deny access that is granted by lower-level policies.
- [x] IAM policies that are implemented by lower-level policies can override the policies defined at a higher level.

#### Q5. Which way of accessing Google Cloud lets you control services through the code you write?
- [x] APIs
- [ ] The Cloud Console mobile app
- [ ] The Cloud Console
- [ ] The Cloud SDK and Cloud Shell

#### Q6. When would you choose to have an organization node? (Select two)
- [x] When you want to centrally apply organization-wide policies
- [ ] There’s no choice; organization nodes are mandatory.
- [x] When you want to create folders
- [ ] When you want to organize resources into projects
**Explanation:**  Organization nodes let you apply policies centrally. Folders require an organization node

#### Q7. Which statement best describes how Google Cloud resources are associated within the resource hierarchy?
- [ ] All Google Cloud resources are associated with an organization.
- [ ] Google Cloud resources are not associated with the resource hierarchy.
- [x] All Google Cloud resources are associated with a project.
- [ ] All Google Cloud resources are associated with a folder.
**Explanation:**  All Google Cloud resources are associated with a project.

#### Q8. What is the difference between Identity and Access Management (IAM) basic roles and IAM predefined roles?
- [ ] Basic roles only apply to the owner of the Google Cloud project. Predefined roles can be associated with any user.
- [ ] Basic roles can only be granted to single users. Predefined roles can be associated with a group.
- [ ] Basic roles only allow viewing, creating, and deleting resources. Predefined roles allow any modification.
- [x] Basic roles affect all resources in a Google Cloud project. Predefined roles apply to a specific service in a project.
**Explanation:**  Organization nodes let you apply policies centrally. Folders require an organization node		



# Topic 3:
## Quiz Questions
#### Q1. Which term describes a secure, individual, private cloud-computing model hosted within a public cloud?
- [ ] Domain name system (DNS)
- [ ] Content delivery network (CDN)
- [x] Virtual private cloud (VPC)
- [ ] Virtual private network (VPN)

#### Q2. A Google Cloud customer wants to load-balance traffic among the backend VMs that form part of a multi-tier application. Which load-balancing option should this customer choose?
- [ ] The global SSL proxy
- [ ] The global TCP proxy
- [ ] The global HTTP(S) load balancer
- [ ] The regional load balancer
- [x] The regional internal load balancer

#### Q3. Select the true statement about Google’s VPC networks and subnets.
- [ ] Networks are global, and subnets are zonal.
- [x] Networks are global, and subnets are regional.
- [ ] Networks are regional, and subnets are zonal.
- [ ] Both networks and subnets are global.

#### Q4. Which interconnect option is a service level agreement (SLA) available for?
- [ ] Standard Network Tier
- [ ] Direct Peering
- [x] Dedicated Interconnect
- [ ] Carrier Peering

#### Q5. Which statement best describes how VPC routers and firewalls work?
- [x] They are managed by Google as a built-in feature.
- [ ] Customers provision virtual machines and run their routers and firewalls in them.
- [ ] They are managed by Google in virtual machines and customers can tune or deactivate them.
- [ ] They are managed by Google in virtual machines and customers cannot modify them.

#### Q6. Preemptible VMs can offer advantages over a standard Compute Engine VM. What is a reason customers choose preemptible VMs?
- [ ] To use custom machine types
- [ ] To reduce cost on premium operating systems
- [x] To reduce cost
- [ ] To improve performance
**Explanation:**  The per-hour price of preemptible VMs incorporates a substantial discount.

#### Q7. An application running in a Compute Engine virtual machine needs high-performance scratch space. Which type of storage meets this need?
- [ ] Cloud Storage bucket
- [ ] Regional persistent disk
- [ ] Zonal persistent disk
- [x] Local SSD


# Topic 4:
## Quiz Questions
#### Q1. Which database service can scale to higher database sizes?
- [ ] Cloud SQL
- [ ] Bigtable
- [ ] Firestore
- [x] Cloud Spanner

#### Q2. Which statement describes the correct Cloud Storage use case?
- [ ] Cloud Storage provides RDBMS (Relational Database Management System) services.  
- [x] Cloud Storage provides durable and highly available object storage.
- [ ] Cloud Storage provides data warehousing services.
- [ ] Cloud Storage provides the root file system of a Linux virtual machine.

#### Q3. You manufacture devices with sensors and need to stream huge amounts of data from these devices to a storage option in the cloud. Which storage option is the best choice for your application?
- [x] Bigtable
- [ ] BigQuery
- [ ] Cloud Spanner
- [ ] Firestore

#### Q4. How are Firestore and Bigtable alike? (Select two answers.)
- [x] They are both NoSQL databases.
- [ ] They both offer SQL-like queries.
- [ ] They both have a free daily quota.
- [x] They are both highly scalable.

#### Q5. Your application needs to store data with strong transactional consistency, and you want seamless scaling up. Which storage option is the best choice for your application?
- [ ] Cloud Storage
- [ ] Firestore
- [x] Cloud Spanner
- [ ] Cloud SQL

#### Q6. Why would a customer consider the Coldline Storage class?
- [x] To save money on storing infrequently accessed data
- [ ] To improve security
- [ ] To use the Coldline Storage API
- [ ] To save money on storing frequently accessed data


# Topic 5: 
## Quiz Questions
#### Q1. What is a Kubernetes pod?
- [ ] A group of VMs
- [ ] A group of clusters
- [ ] A group of nodes
- [x] A group of containers

#### Q2. Where do the resources used to build Google Kubernetes Engine clusters come from?
- [ ] Cloud Storage
- [x] Compute Engine
- [ ] App Engine
- [ ] Bare metal servers

#### Q3. What is a Kubernetes cluster?
- [x] A group of machines where Kubernetes can schedule workloads.
- [ ] A group of containers that provide high availability for applications.
- [ ] A group of pods that manage the administration of a Kubernetes application.

#### Q4. Anthos provides a rich set of tools for monitoring and maintaining the consistency of your applications across which of the following locations?
- [x] Applications hosted on-premises, in the cloud, or in multiple clouds.
- [ ] Applications hosted with one cloud provider only.
- [ ] Applications hosted on-premises only.
- [ ] Applications hosted with multiple cloud providers only.

#### Q5. How do you keep your Kubernetes version updated in Google Kubernetes Engine?
- [ ] You cannot update a running cluster. You need to create a copy of the cluster with the updated Kubernetes version.
- [ ] You are required to set up a cron job to periodically check the Kubernetes version in your cluster.
- [x] The Google Kubernetes Engine team periodically performs automatic upgrades of your cluster to newer stable versions.
- [ ] You need to stop your cluster and manually update the Kubernetes version in your cluster.

#### Q6. Select two reasons for using containers to deploy applications. (Choose 2 responses.)
- [x] Migrating workloads is simpler.
- [ ] It provides tight coupling between applications and operating systems.
- [x] It creates consistency across development, testing, and production environments.
- [ ] Allocating resources in which to run containers is not necessary.

#### Q7. How do containers access an operating system?
- [ ] Containers use a shared base operating system stored in a shared runtime layer.
- [x] Containers use a shared base operating system stored in a shared kernel layer.
- [ ] Each container has its own instance of an operating system.
- [ ] Containers use a shared base operating system stored in a Cloud Storage bucket.


# Topic 6:
## Quiz Questions
#### Q1. App Engine is best suited to the development and hosting of which type of application?
- [ ] Applications that require at least one instance running at all times
- [ ] Applications that require full control of the hardware they are running on
- [ ] A long-running batch processing application
- [x] A web application


#### Q2. Which statements are true about App Engine? (Select 2).
- [ ] App Engine charges you based on the resources you preallocate instead of the resources you use.
- [x] The daily billing for an App Engine application can drop to zero.
- [ ] App Engine requires you to supply or code your own application load balancing and logging services.
- [ ] Developers who write for App Engine do not need to code their applications in any particular way to use the service.
- [x] App Engine manages the hardware and networking infrastructure required to run your code.

#### Q3. Select the managed compute platform that lets you run stateless containers through web requests or Pub/Sub events.
- [x] Cloud Run
- [ ] Cloud Source Repositories
- [ ] Cloud Endpoints
- [ ] Apigee Edge

#### Q4. Which Google Cloud service should you choose to perform business analytics and billing on a customer-facing API?
- [ ] Cloud Run API
- [ ] Compute Engine API
- [x] Apigee Edge
- [ ] Cloud Endpoints

#### Q5. What are the advantages of using App Engine’s flexible environment instead of its standard environment? (Select 3).
- [ ] Google provides automatic in-place security patches.
- [x] You can install third-party binaries.
- [ ] Your application can execute code in background threads.
- [x] Your application can write to the local disk.
- [x] You can use SSH to connect to the virtual machines on which your application runs.

#### Q6. Cloud Run can only pull images from:
- [ ] GitHub
- [ ] Self-hosted registries
- [x] Artifact Registry
- [ ] Docker Hub


# Topic 7:
## Quiz Questions
#### Q1. Why might a Google Cloud customer choose to use Cloud Functions?
- [x] Their application contains event-driven code that they don't want to provision compute resources for.
- [ ] Cloud Functions is a free service for hosting compute operations.
- [ ] Their application has a legacy monolithic structure that they want to separate into microservices.
- [ ] Cloud Functions is the primary way to run Node.js applications in Google Cloud.

#### Q2. Why would a developer choose to store source code in Cloud Source Repositories? (Select 2)
- [ ] It is the only way to access your source code in a repository
- [x] To reduce work
- [x] To keep code private to a Google Cloud project
- [ ] To have total control over the hosting infrastructure

#### Q3. Why might a Google Cloud customer choose to use Terraform?
- [x] Terraform can be used as an infrastructure management system for Google Cloud resources.
- [ ] Terraform can be used as an infrastructure management system for Kubernetes pods.
- [ ] Terraform can be used to enforce maximum resource utilization and spending limits on your Google Cloud resources.
- [ ] Terraform can be used as a version-control system for your Google Cloud infrastructure layout.

#### Q4. Select the advantage of putting the event-driven components of your application into Cloud Functions.
- [ ] In Cloud Functions, code can be written in C# or C++.
- [ ] Cloud Functions eliminates the need to use a separate service to trigger application events.
- [ ] In Cloud Functions, processing is always free of charge.
- [x] Cloud Functions handles scaling these components seamlessly.


# Topic 8:
## Quiz Questions
#### Q1. Which definition best describes a service level indicator (SLI)?
- [ ] A contract with your customers regarding service performance
- [x] A time-bound measurable attribute of a service
- [ ] A percentage goal of a measure you intend your service to achieve
- [ ] A key performance indicator; for example, clicks per session or customer signups

#### Q2. You want to create alerts on your Google Cloud resources, such as when health checks fail. Which is the best Google Cloud product to use?
- [ ] Cloud Trace
- [ ] Error Reporting
- [x] Cloud Monitoring
- [ ] Cloud Functions

#### Q3. Which option describes a commitment made to your customers that your systems and applications will have only a certain amount of “downtime”?
- [x] Service level agreement
- [ ] Service level objective
- [ ] Service level indicator
- [ ] Key performance indicator

#### Q4. There are “Four Golden Signals” that measure a system’s performance and reliability. What are they?
- [ ] Get, post, put, delete
- [ ] Availability, durability, scalability, resiliency
- [x] Latency, traffic, saturation, errors
- [ ] KPIs, SLIs, SLOs, SLAs

#### Q5. Select the two correct statements about Cloud Logging.
- [ ] Cloud Logging requires you to store your logs in BigQuery or Cloud Storage.
- [x] Cloud Logging lets you view logs from your applications and filter and search on them.
- [ ] Cloud Logging requires the use of a third-party monitoring agent.
- [x] Cloud Logging lets you define metrics based on your logs.
- [ ] Cloud Logging lets you define uptime checks.




Disclaimer: These answers are not leaked. These are just what i think are correct to the best of my knowledge.

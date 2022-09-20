## Latihan - Minggu 01


### Rangkuman Artikel 1
``What is the difference between IaaS, SaaS, and Paas?``

You make your own cheese, toppings, pizza dough, have your own oven, gas, etc. and you do everything yourself and eat at home. In the case of IaaS, you buy the raw materials from your cloud service provider. The infrastructure would be provided to you by the cloud provider you would not have full control over it. 

In PaaS, you buy pizza from outside and eat at home - i. They are provided to you as managed services by your cloud service provider. In the SaaS model, most services are through your service provider and the amount of setup or installation on your end is minimal.

### Rangkuman Artikel 2
``SAAS (Software as a Service) Platform Architecture``

How SaaS Affects IT ?
After you’ve made the decision to pursue SaaS, the next is to prepare for the transition by assessing how the deployment will affect existing IT assets. Performing due diligence is a routine part of any successful IT infrastructure deployment project. Assess your data-security needs, and ensure that the provider has measures in place to meet the standards you set.

Impact on IT Roles and Responsibilities
Adding SaaS can cause a fundamental shift in the IT department’s role as a provider of information services. In the past, the nature of software deployment has put chief information officers in the role of gatekeepers .

### Rangkuman Artikel 3
``What is Software as a Service SaaS Architecture``

Wondering about Software as a Service SaaS architecture?

The delivery of software has changed over the years. Historically, applications were written for mainframes in languages such as COBOL. Finally, we saw the development of more advanced services including multi-tenant architecture that is run and accessed via remote ‘cloud’ servers. It was during this time that we saw a paradigm shift in the way in which software was being built and made available to the end consumer.

No longer did consumers have to download and install an application onto their machine to run it. Powered by cloud computing, consumers and businesses could use services over the web in just a few mouse clicks. SaaS was born – Software as a Service. Whether you’re new to SaaS, an experienced developer, or CTO, we’re sure you’ll find this article on SaaS application architecture interesting.

A visual representation of how the SaaS model operates

SaaS is a way to deliver software, the provider of the software centrally hosts one or more applications and makes them available to customers over the internet. SaaS architecture is also one of the main pillars of cloud computing.

THE SIMPLICITY OF SAAS ARCHITECTURE APPS

Software applications architected as SaaS solutions are typically accessed over the web through various types of devices.

ECONOMICAL VALUE

As a consumer of an application architected using SaaS, you don’t need to concern yourself with how your data is being locked down.

COMPATIBILITY

With traditional software installations, updates and patches can occasionally require enormous amounts of time and money.

Capabilities Of SaaS Solutions

Infrastructure that would have historically been physically installed on business premises and run by internal IT teams, can now be provisioned from an online dashboard with just a few mouse clicks.

LIMITED ECOSYSTEM

That said, there are still many applications that don’t offer a hosted version.

SCALABILITY

Well-designed SaaS applications need to be able to do this. From a software architecture perspective, you can introduce a separation of concerns by having individual layers to handle data access, business logic, and the presentation layers of your application which will help your application scale more easily.

### Rangkuman Artikel 3
``How to build a cloud-based SaaS application``

Build for the cloud

When building a SaaS application chances are high that you're building it in the cloud. Here's how to build up a cloud-based SaaS architecture.

Which programming language?

And we ended up using Python. Python is a widely used programming language, designed to emphasize on its code readability. Python can do a lot of things. Whatever web app you’d like to build, there’s likely a framework for it in Python.

We at Usersnap had quite some experience with Python before using it for our web app. As mentioned, it’s flexibility for various use cases was yet another reason for us to jump on Python. Python is great and our developers love it. Everything’s possible with Python.

Python is a safe bet.

Why choose a document-oriented database?

And it often reduces database sizes. In summary, the DOB concept offers a richer experience with modern programming techniques. We – at Usersnap – ended using MongoDB as our prior database. Because MongoDB is a document-oriented database that provides high performance, high availability, and easy scalability.

Besides performance , scalability is the most important factor for us as a global SaaS business. A lot of SaaS founders aim for scaling their business. Scaling your tech with MongoDB is pretty easy . And MongoDB uses sharding to support deployment with large datasets.

Getting started with MongoDB we installed a single MongoDB instance on our AWS EC2 instance in Ireland. Therefore, we installed a master/slave architecture with the master still in Ireland and added two MongoDB slave instances in the US West Coast and Singapore. Writes still go directly to the master DB and get replicated to the slaves automatically by MongoDB.

Queuing system for your SaaS application

Let’s talk about a queuing system now. A message queuing system is an asynchronous communication protocol, enabling sender and receiver of a message not interacting at the same time. A message queue has limits regarding the size and amount of data transmitted in the queue.

Web Storage S3

With the Amazon S3 storage service, we have a great, and highly scalable object storage installed. Amazon Simple Storage Service is easy to use, store and retrieve any amount of data. Besides storing your data of your web app with S3, it might work great for database backups, archives or big data analytics.

Content Delivery Network for your SaaS application

A content delivery network is basically a system of distributed servers which enables you to serve content to your app users with high performance and high availability. Below you can find an overview how we at Usersnap have set up our web app and the role of EC2, S3, and CDN.

Recap: SaaS application set up

With Python, MongoDB – as a great document-orientated database, RabbitMQ software-wise the basic setup is done.

Start with software testing now

This article was brought to you by Usersnap – your feedback and bug tracking tool. Used by software companies like Facebook, Google, and AddThis. Read this blog post about how Usersnap helps during your SaaS application development. And if you’re ready to try out a customer feedback software, Usersnap offers a free trial.
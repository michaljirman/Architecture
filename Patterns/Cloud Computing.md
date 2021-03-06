# Cloud Computing:

* Per [IBM](https://www.ibm.com/cloud/blog/cloud-computing-history), the idea of "Cloud Computing" dates all the way back to 1950!

* [A Brief History](https://docs.google.com/presentation/d/1BoxFeENJcINgHbKfygXpXROchiRO2LBT-pzdaOFr4Zg/edit#slide=id.g39c264972c_182_1000)

Cloud (& Edge) native technologies empower organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. **Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach.**

These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.
-- [CNCF Cloud Native Definition](https://www.cncf.io/)

1. Separation of Compute & Storage
2. Network topology, Authentication, Cloud resource provisioning, Deployment, Logging and Monitoring, Traffic routing, Rate limiting, Staging and Production environments.

Programs are optimized for managing [cross-cutting concerns](https://dl.acm.org/doi/pdf/10.1145/3190508.3190526) in an intuitive and obvious manner, with feature requirements coded on one axis and common concerns on the other.

### 1. Security

* Data - Sensitive data, Personally identifiable information - PII, PCI or PHI 

* Services - 11 security patterns for microservice architectures - all in one handy guide! - https://developer.okta.com/blog/2020/03/23/microservice-security-patterns
    
### 2. Manage State

* [Stateful](Stateful.md)
  
## Metrics
**High Performance System** - How you [Structure & Monitor Measurements](https://www.youtube.com/watch?v=lJ8ydIuPFeU) radically alters what numbers you'll see, and it's extremely counterintuitive if you don't think long & hard.
 1. [User-centric meaningful availability](https://www.usenix.org/system/files/nsdi20spring_hauer_prepub.pdf)
 2. https://web.dev/vitals/
 * https://web.dev/milliseconds-make-millions/
 
## Insights & Trends - In the future the majority of managed infrastructure offerings will be backed by open interfaces, but not necessarily open source projects.

* [SCREAMING IN THE CLOUD](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/)
  * On the future of @Kubernetesio “We'll enter another phase where you'll build a platform on top of Kubernetes, but it won't be worth mentioning that Kubernetes is underneath. People will be more interested in the thing above.” 
* https://www.youtube.com/watch?v=ZVRI214nnto
* [Standards](https://docs.google.com/presentation/d/1wc9nJSyfjrUO2KpVgXt5KnSHVlWvXpho6eINkin5U5g/edit#slide=id.g12bfb019f3_2_34)
* [Open Application Model](https://oam.dev/)
* [Decouple developers from operations](https://www.youtube.com/watch?v=do-PrVi0ifk)
* [Kafka Cloud Native](https://www.confluent.io/blog/introducing-cloud-native-experience-for-apache-kafka-in-confluent-cloud)
* [Cassandra Cloud](https://constellation.datastax.com/)
* [Amazon Aurora cloud-native relational database](https://www.allthingsdistributed.com/2019/03/Amazon-Aurora-design-cloud-native-relational-database.html)
* [Socrates: The New SQL Server in the Cloud](https://www.microsoft.com/en-us/research/uploads/prod/2019/05/socrates.pdf)
* [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
* [Cloud Native Blog](https://blog.container-solutions.com/)
   * https://github.com/ContainerSolutions
* The Amazon Effect
   * [Open Source at AWS](https://aws.amazon.com/opensource)
   * [Commercial Open Source Software](https://coss.media/oss-will-eat-cloud-computing/)
   * [Fork and Commoditize](https://thenewstack.io/fork-and-commoditize-gitlab-ceo-critiques-the-new-open-source-approach-by-amazon-web-services/)
   * [AWS Well-Architected Labs](https://wellarchitectedlabs.com)
   * [Amazon Builders Library](https://aws.amazon.com/builders-library/)
   * [AWS Well-Architected Framework](https://wa.aws.amazon.com/index.en.html)
   * https://www.honeycode.aws/
   
   * [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/) is not just Open Source C*/CQL compatibility. It's also potentially Change Data Capture (CDC) integrated w/ EventHub & Compute (Serverless) used for Data Lake
  * https://aws.amazon.com/blogs/database/introducing-the-aurora-storage-engine/
  * https://www.alibabacloud.com/blog/lindorm-alibaba-clouds-newest-cloud-native-multi-model-database_596269?spm=a2c65.11461433.0.0.46a75355aeZ2GL
  
* [GitHub](https://github.blog/category/community/insights/)

* [Serverless Function (FaaS)](https://fauna.com/blog/comparison-faas-providers)

# 

**Manage, [Planes - Control & Data](http://brooker.co.za/blog/2019/03/17/control.html)**

* **Multi-cloud**
  * [Crossplane](https://crossplane.io) - open source universal control plane on which any platform can be built and configured through Kubernetes style APIs;is open source/open governance, supports multiple cloud/infra providers, support application self-servicing, enables a clean separation of concern, and more.
  
  * [Crossplane](https://github.com/crossplane/crossplane) “introduces a powerful open source control plane to enterprise platforms, enabling companies to standardize on application and infrastructure management; automate operations; effectively implement their security, governance, and cost policies; and publish an internal API that integrates with their development workflows and tools.”

  * AWS [Outposts](https://aws.amazon.com/outposts/)
  * Azure [Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) - Appliance, ...
  * GCP [Anthos](https://inthecloud.withgoogle.com/content-anthos/dl-cd.html) - OSS components, Kubernetes, Istio, Knative, Cloud Run ...

* **Sidecar** - Cross-cutting concerns in a [**sidecar**](https://microservices.io/patterns/deployment/sidecar.html) process or container that runs alongside the service instance. [Operators and Sidecars Are the New Model for Software Delivery](https://thenewstack.io/operators-and-sidecars-are-the-new-model-for-software-delivery/)
  
  * [DAPR, Distributed Application Runtime](https://dapr.io/)
Azure is launching Dapr a Open Source portable runtime for building applications in cloud and edge, Dapr is a a collection of really useful side-cars to make your distributed app development easier!
  * [KEDA, Kubernetes Event-driven Autoscaling](https://keda.sh)
  * [Kubernetes native applications](https://operatorhub.io)
  * [Secure networking](https://www.projectcalico.org)
  * [API Shark, Service Catalog & Call Graph](https://www.cloudvector.com/api-shark/)
  * ...
  
* **Service Mesh** - This design pattern combines [data planes & control planes](https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc)
  * [GCP, Cloud Run](https://cloud.google.com/run/)
  
* **Scheduler** - Smart Schedulers on top of an orchestrator with tasks encapsulated & labelled
  * [Green Scheduler](https://blog.google/inside-google/infrastructure/data-centers-work-harder-sun-shines-wind-blows/)
  
* [What happens when I type kubectl run?](https://github.com/jamiehannaford/what-happens-when-k8s)
* [10 must-know patterns](https://developers.redhat.com/blog/2020/05/11/top-10-must-know-kubernetes-design-patterns/2901820597/) 

**Frontend**

* [JAMStack](https://snipcart.com/blog/jamstack)
  * ["The big part of it is that it's prerendered and served without web servers :) You can use APIs and Serverless functions for dynamicism, it's not required."](https://codepen.io/sdras/full/NWqNBzV)   

**Backend - Holistic approach**

* https://ballerina.io/
* [Dark](https://medium.com/darklang/the-design-of-dark-59f5d38e52d2) - Dark is a programming language and platform that enables building serverless backends. There’s no infra, framework or deployment nightmares. It’s a new paradigm in software delivery.

Tehnology Radar - https://www.thoughtworks.com/radar/platforms
* https://www.thoughtworks.com/radar/platforms/knative

**AI Assisted Coding** - [Kite](https://www.kite.com/), because we spent too much time on repetitive work like copying and pasting from StackOverflow, fixing simple errors, and writing boilerplate code. Now the power of AI is available for JavaScript & Python devs!


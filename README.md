<font size="16">
 
# Modern Application Development
### - Time To Value 

# Big Enterprise:
## <p align="center"> <b> "enterprises buy everything. If you're big enough and you have a big enough IT budget, most enterprises have a POC of everything that's for sale, period. There's some team in some pocket, maybe they came through via acquisition. Maybe they live in a different state. Maybe it's just a new project that came out. And what you tend to see, at least from my experiences, if I walk into a typical enterprise, they may tell me something like, "Hey, we have a POC, a Pivotal Cloud Foundry, OpenShift, and we want some of that new thing that we just saw from you guys. How do we get a POC going?" </b> </p> [- Kelsey Hightower, principal developer advocate at Google](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/the-staying-power-of-kubernetes-with-kelsey-hightower/)

## Big O's:
### 1. Software: Greenfield & Brownfield
### 2. Legacy: "it makes actual money"
### 3. Cloud: Early days

## Improvements: 
[![Systems Thinking](https://github.com/ankumar/Architecture/blob/master/images/Russell%20Ackoff.png)](https://www.youtube.com/watch?v=OqEeIG8aPPk "Dr. Russell Ackoff")
## <p align="center"><b>Systems Thinking: "If we have a system of improvement that’s directed at improving the parts taken separately, you can be absolutely sure that the performance of the whole will not be improved. The performance of a system depends on how the parts fit, not how they act taken separately.” <b>- Dr. Russell Ackoff.</b></p>
  
![](https://github.com/ankumar/Architecture/blob/master/images/wardley.jpeg)

- Architecture is about **Systems Thinking** including People, Process and Technology; synthesis of multiple perspectives, including social dynamics, domain-driven design, business models, and software architecture. It's not about code, and it's not a synonym for "software architecture":

- Anything is possible for a company when its culture is about listening, learning, and harnessing individual passions and talents to the company’s mission." - Satya Nadella

## **1. Technology needs to be embedded in the Business not external to it or merely aligned with it**
         - Work backwards from Customer/Business outcomes
         - Build closed loop systems to optimize for continual Improvements & Learning
         - Technology Commoditization
## **2. Focus on core value vs plumbing:**
         - Business mapped into technologies that underpin the delivery of that core value 
         - Seeing Custom & Commodity technologies in the value chain
         - Custom to Commodity & Viceversa to increase the value delivery for lower cost

## Architecture:
### 1. Services 
* Designing Modularity & Interfaces
* Decomposing an Application into Services & APIs

![](https://github.com/ankumar/Architecture/blob/master/images/Microservices1.jpg)

[Microservices](https://www.youtube.com/watch?v=wgdBVIX9ifA) - also known as the microservice architecture - is an architectural style that structures an application as a collection of services that are

**1. Highly maintainable & testable** <br>
**2. Loosely coupled** <br>
**3. Independently deployable** <br>
**4. Organized around business capabilities** <br>
**5. Owned by a small team**<br>
![](https://images.ctfassets.net/ro61k101ee59/2bmS9TVlJc5einK9YLBY3V/992367961e649dd0343a3486616601fd/Image-1.png?w=1348&q=90)
<p align="center"> <a href="https://monzo.com/blog/we-built-network-isolation-for-1-500-services">Modern Bank, Monzo: 1,500+ services</a> </p>

## **There isn't a concrete, well-defined algorithm for decomposing a system into services. As with much of software development, it's something of an art. If you decompose a system incorrectly, we have a distributed monolith, a system consisting of coupled services that must be deployed together. A distributed monolith has the drawbacks of both the monolithic and the Microservices architectures.**

## > Devs to focus on Business logic, Hiding Distributed systems complexity, Examples:
* https://cloud.google.com/run/
* https://dapr.io/
* https://oam.dev/

### 2. Software 2.0

### Data powers new innovations, improvements in customer experience, and efficiency. Small advantage in data and algorithms result in increased customers/business success which in turn results in more data. This virtuous cycle due to positive feedback loop amplifies a company's competitive advantage, making data one of the key ingredients in building companies that have Increasing Returns instead of commonly seen Decreasing Returns.

![](https://miro.medium.com/max/1372/1*zOp70MCQ-uhaS7lUVAhATA.png)

### Advances in machine learning (ML) over the last decade have opened up a radically new approach to building software systems. Dubbed [“Software 2.0”](https://medium.com/@karpathy/software-2-0-a64152b37c35), this approach focuses on training models to learn from data instead of explicitly writing code for the required behavior. 

## <p align="center"> <b> "In traditional software engineering, or Software 1.0, a program’s functionality is defined via code as dictated by a human. In the age of machine learning, we are increasingly observing Software 2.0 systems, where a program’s functionality is defined by the weights of neural networks as dictated by the data. You wouldn’t trust a piece of human-written code that hasn’t ever been debugged or tested, so why shouldn’t our data receive the same treatment now that it’s a first-class citizen in so many real-world systems?"

## > Data Validation 
Data quality problem categories:
- Data creation
- Data labelling
- Data manipulation
- Data quality evaluation
## > Software Engineering Practices, Examples:
* https://algorithmia.com/enterprise
* https://algorithmia.com/blog/introducing-github-source-code-management-for-algorithmia
</b> </p>

### 3. Open Source > [Inner Sourcing - Open source best practices within organization](https://github.com/InnerSourceCommons/InnerSourcePatterns)
## - “if you want to go fast go alone, but if you want to go far, go together”
## - " "new model" is a big increase in end user corporations contributing to and producing their own open source projects. That's where the resources are coming from, and it's part of the success of Netflix, Capital One, Lyft, Airbnb that is spreading. ” <p align="right"><b>- Adrian Cockcroft, VP Cloud architecture strategy at Amazon Web Services</b></p>
## <p> <b>- Cloud would not have been possible without open source</b> </p>
## - Developers - Over 1.3 million first time contributors joined the open source community
* [2019 Octoverse report](https://octoverse.github.com/)
* [2018 Octoverse report](https://octoverse.github.com/2018/)
## - Community & Company Driven [Projects](https://www.linuxfoundation.org/projects/)
## - Open [Governance](https://github.com/cncf/toc/), Stewardship & [Principles](https://github.com/cncf/toc/blob/master/PRINCIPLES.md#toc-operating-principles)
### <p align="left"> <b> "it's not a race it's a marathon" </b> </p>
[![It's not a race if we're all on the same team](https://github.com/ankumar/Architecture/blob/master/images/Kelsey%20Hightower.png)](https://www.youtube.com/watch?v=jiaLsxjBeOQ "Kelsey Hightower, Staff Developer Advocate, Google")
### <p align="right"> <b> ".........it's not a race if we're all on the same team" </b> </p>

### 4. Cloud Computing > [Service Model - SaaS](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
## - On the future of @Kubernetesio “We'll enter another phase where you'll build a platform on top of Kubernetes, but it won't be worth mentioning that Kubernetes is underneath. People will be more interested in the thing above.”
|Characteristics|Developer Productivity|
|------------------------| ---------------------------------------------------------------------------------------------|
| **On-demand self-service** | A consumer can unilaterally provision computing capabilities, such as server time and network storage, as needed automatically without requiring human interaction |
|**Broad network access**|Capabilities are available over the network and accessed through standard mechanisms|
|**Resource pooling**|The provider’s computing resources are pooled to serve multiple consumers using a multi-tenant model, with different physical and virtual resources dynamically|
|**Rapid elasticity**|Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand|
|**Measured service**|Cloud systems automatically control and optimize resource use by leveraging a metering capability (typically per-per-use)|

![](https://github.com/ankumar/Architecture/blob/master/images/CNCF.png)<p align="center"> </p>
[![Opensource's value and collaborating with cloud vendors](https://github.com/ankumar/Architecture/blob/master/images/databricks-opensource.png)](https://dbricks.co/ex200221a, "")
### <p align="right"><b>- Ali Ghodsi, Co-founder & CEO at data science, big data processing and machine learning company Databricks.</b></p>
#
## [> References ...](https://github.com/ankumar/Architecture/blob/master/Patterns/Stuff.md)
</font>

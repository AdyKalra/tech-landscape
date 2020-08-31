## Tech Landscape
* ### 📚 Capability catalog 
    * Explore technical, process, measurement, and cultural capabilities which drive higher software delivery and organizational performance.
    * Each of the areas below presents a capability, discusses how to implement it, and how to overcome common obstacles and answer the "How to Transform"
* **Technical**
    * Requirements management, design and development services across a portfolio of applications and supporting frameworks.
    * Feasibility studies, time and cost estimates, and the establishment and implementation of new or revised applications systems and platforms
    * Going 100% on cloud and having a cloud first approach
* **Process**
   * High quality self-service channel for our users
   * Streamlining Change Approval
   * Visibility of Work in Value Stream
   * Working in smaller batches / Process limits 
* **Measurement**
    * Forecasting and defining  software and hardware requirements to cater to business needs 
    * Monitoring and Proactive failiure notification
    * Engineering efficiency
* **Cultural**
    * Assign personnel to various projects and directs activities
    * Moving offshore teams and establishing greenfield teams here
    * Reviews and evaluate work
    * Learning Culture
* **Strategic**
    * Strategic direction of product, services and technology
    * Product optimisation and implementation
    * Modernisation and uplift of our software development practices
    * Disparate / aging UIs
    * Transformation of Technology stack toward digital services
    * Technology debt remediation 
 
**Legend:** ⭐⭐⭐ -  Significant ⭐⭐ - Insightful ⭐ - Good to know

<details>
<summary>🔧 Technical</summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |
| | **The Big Picture / Practices** |
| [High Level Design](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/High%20Level%20Design.md)| Overview of Client -> CDN / DNS -> LB -> Http Cache -> APIG -> XL -> Feature Services -> Core Services -> Domains |⭐⭐⭐ |
| [Stackshare tools](https://stackshare.io/categories) | All the best open source and Software as a Service (SaaS) tools in one place |⭐⭐ |
| | **Front-end Development Practice** |
| [Front-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | concepts - hoisting, event bubbling, scope prototype, shadow DOM. package managers - npm, yarn. CSS, BEM, Saas, Postcss.build tools - npm nuild, module bundlers webpack, linters and formatters, React Angualr Vue, modern css, css frameworks - reactstrap, mterialUI, Testing - Jest Cypress Mocha Chai. Progressive TypeScript, Server Side Rendering , GraphQL. ReactNative , Flutter , Static site generators  |⭐⭐⭐|
| | **Back-end Development Practice** |
| [Back-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | C#, Java, Go, Python. Realational , NoSQL , Data Sharding , Replication , CAP. Authentication Oauth, token , JWT, SAML. apis - JSON, SOAP. Caching - DNS , serverside, clientside - Redis, MemCached. Design practices - GOF , DDD , TDD , SOLID, KISS , YAGNI, DRY. Architectural patterns - Microservices, SOA, Serverless. Messagebrokers , RabbitMQ , Kafka. Containers - Docker , GarphQL, Neo4j. |⭐⭐⭐|
| | **Testing Practice** |
| [Testing Raodmap](https://github.com/anas-qa/Quality-Assurance-Road-Map) | Test Plan template, testing startegies, testing types, TDD , automation - mobile , web , API , contrct testing Packt, Testing Pyramid , Gap Analysis , Customer Insights , E2E regression suite |⭐⭐⭐|
| | **Mobile Development Practice** |
|[android roadmap](https://roadmap.sh/android) |Kotlin , Java |⭐⭐|
| | **DevOps Practice** |
| [Devops Roadmap](https://github.com/kamranahmedse/developer-roadmap) | Pytho, Ruby , NodeJS. initd, systemd. OS - Linus , FreeBSD. Terminal - maniupaltion tools,, BASH, vim, network. Protocosl - http, ftp, ssh. Reverseproxy, Caching server, Forward Proxy , Load balancer, firewall. Webserver - Nginx, Service Mesh - Istio. Containers, Config mgmt, container orchestration, Infra provisioning. CI/CD tools, Infra monitoring - Prometheus , Nagios, Grafana. Appln Monitoring - NewRelic , AppDynamics. Log Mgmt - Elastic stalk, splunk sumo. Cloud - AWS , GCP, Azure. Cloud Design Patterns - Availability , Data Management.  |⭐⭐⭐|  
| | **Architecture Practice** |
| [Architecture decision records](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/ADRs.md) | document how and why a decision was reached within a codebase.|⭐⭐|
|[Serverless Microservice Patterns for AWS](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Design%20Patterns%20-%20Serverless.md)|Serverless Ecosystem, best practices , patterns|⭐⭐⭐|
|[Domain-Oriented Microservice Architecture](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Domain-Oriented%20Microservice%20Architecture.md)| DOMA core principles and terminology, the Why, Uber's implementation|⭐⭐⭐|
|[API Design Cheat Sheet](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/API%20Design%20Cheat%20Sheet.md)| Best practices / Principles for API Design|⭐⭐|
|[Backend for Frontend design pattern](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/BFF.md)|f developing niche backends for each user experience, While an API Gateway is a single point of entry into the system for all clients, a BFF is only responsible for a single type of client|⭐⭐|
|[Choreography vs Orchestration in the land of serverless](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Choreography%20vs%20Orchestration%20-%20serverless.md)| (the ‘orchestrator’) that controls the interaction between services. It dictates the control flow of the business logic and is responsible for making sure that everything happens on cue. This follows the request-response paradigm. In choreography, every service works independently. There are no hard dependencies between them, and they are loosely coupled only through shared events. Each service listens for events that it’s interested in and does its own thing. This follows the event-driven paradigm.|⭐|
|[DLQ](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/DLQ.md)|handling message failure.Message that is sent to a queue that does not exist. Queue length limit exceeded.Message length limit exceeded.Message is rejected by another queue exchange.|⭐|
| [Design Patterns - Frontend](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Design%20Patterns%20-%20Frontend.md) | Design Patterns - Frontend |⭐⭐⭐|
| [Function as a Service](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Function%20as%20a%20Service.md) |Microsoft Azure Functions, Lambdas, Google Cloud Functions, etc |⭐|
| [Kafka vs Kinesis](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Kafka%20vs%20Kinesis.md) | Kafka vs Kinesis|⭐⭐|
| [Micro Frontends](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Micro%20Frontends.md) |extending the principles of Microservices to frontend development.Enable rapid, frequent, and reliable delivery of large, complex applications by separating backend services into smaller (micro) services organized around the business logic. |⭐⭐|
| [Microservice Architecture](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Microservice%20Architecture.md) |Microservice Architecture is an architectural style that structures an application as a collection of services that are.Highly maintainable and testable.Loosely coupled.Independently deployable.Organized around business capabilities. |⭐⭐⭐| 
| [Decompose by business capability](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Pattern%20:%20Decompose%20by%20business%20capability.md) |Single Responsibility Principle (SRP) defines a responsibility of a class as a reason to change, and states that a class should only have one reason to change. It make sense to apply the SRP to service design as well and design services that are cohesive and implement a small set of strongly related functions. |⭐⭐|
| [Platform-Building Cheat Sheet](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Platform-Building%20Cheat%20Sheet.md) |'platform' is really the method of exposing and growing the digital business model and its offerings. So, the following ground rules define the platform as the digital server-side, back-end data and functionality, leaving the user experiences to be crafted (whether mobile, web or other) on top of that business functionality. Platfrom Ground rules| ⭐⭐|
| [Real world architectures](https://github.com/donnemartin/system-design-primer#real-world-architectures) |Articles on how real world systems are designed.|⭐⭐⭐|
| [Six shifts to create a game-changing data architecture](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Six%20shifts%20to%20create%20a%20game-changing%20data%20architecture.md) |From on-premise to cloud-based data platforms, From batch to real-time data processing, From pre-integrated commercial solutions to modular, best-of-breed platforms, From point-to-point to decoupled data access, From an enterprise warehouse to domain-based architecture, From rigid data models toward flexible, extensible data schemas |⭐|
| | **Ops Practice** |
| []() | | 
</details>

<!--- END OF TOPIC--->

<details>
<summary>📃 Process</summary>

|  Name |  Summary |  
|:-:    |:-:       |
| | **Engineering Challenges** |
| Bug Bash | testing across verticals |
| DevOps culture| transitioning from Devops to CPT  | 
| Web Modernisation| transitioning from legacy PHP to a SPA built on React and NodeJS (tiger team) | 
| Serverless | Going completely serverless |
| | **Change Management** |
| Champions  | lead mini transformations |
| Design Patterns | building a repository of design patterns , BFF / XL , Domain driven design  | 
| | **Customer Insights** |
|  VOC , GA | working backwards from customer insights |  
| | **Mission Team Experimentation** |
| | | 
| | **Visibility of Work in Value Stream** |
| | | 

</details>

<!--- END OF TOPIC--->

<details>
<summary>🔍 Measurement</summary> 
    
|  Name |  Summary | 
|:-:    |:-:       |
| | **Cloud Tools / Practices** |
|[cdk patterns](https://github.com/cdk-patterns/serverless) | SensibleDeafults for Patterns used - all of the official AWS Serverless architecture patterns built with CDK for developers to use |
| [cloudformation](https://github.com/aws-cloudformation/awesome-cloudformation) | cloud formation catalouge - A curated list of resources and projects for working with AWS CloudFormation. https://aws.amazon.com/cloudformation/ |
| [Design Patterns](http://en.clouddesignpattern.org/index.php/Main_Page) | sensible defaults Design Patterns / catalouge - collection of solutions and design ideas for using AWS cloud technology to solve common systems design problems |
| [this-is-my-architecture](https://aws.amazon.com/this-is-my-architecture/?sc_channel=EL&sc_campaign=Explainer_2017_vid&sc_medium=YouTube&sc_content=video942&sc_detail=EXPLAINER&sc_country=US&tma.sort-by=item.additionalFields.airDate&tma.sort-order=desc) | Clarity of bigger picture within Org - Innovative cloud architectures from AWS partners and customers |
| | **Monitoring** |
| | |
| | **Proactive failiure notification** |
| | |
| | **Engineering efficiency** |
| STAX / Cloud Confirmity | cloud compliance and measuring where we are , cost  | 
| Well architected framework | Cloud maturity and assesment | 
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making |

</details>

<!--- END OF TOPIC--->

<details>
<summary>🤝‍ Cultural  </summary>

|  Name |  Summary |   
|:-:    |:-:       |
| | **Recruitment** |
| | |
| | **Reviews and evaluate work** |  
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making |
| Westrum Organisation Culture ||
| | **Learning Culture** |
| | |

</details>

<!--- END OF TOPIC--->

<details>
<summary> 💡 Strategic </summary>

|  Name |  Summary | 
|:-:    |:-:       |  
| | **Engineering Ideas / Techniques ** |
| [engineering roadmaps](https://roadmap.sh/) | all Reference Roadmaps - roadmaps on web |
| [Google Engineering practices](https://github.com/google/eng-practices) | Sensible Deafults template for practices - Google has many generalized engineering practices that cover all languages and all projects. These documents represent the collective experience of various best practices that we have developed over time. |
| Four key metrics | MMTR , Lead Time , Deployment frequency and Change fail rate - Measure engineering team health |
| Gitprime for data driven mindset | Coding Days , Impact , Efficiency , Commits per day , Repos - Data driven engineering metrics |
| Technology Radar | Internal tooling maturity | 
| Engineering maturity assessment | 12 factor app - measure engineering maturity every quarter |
| | **Transformation Challenges** |
| Lack of expertise and exposure |  | 
| pushback from people and existing leaders | |
| missing the overarching strategy across all business units in Digital | |
| new technologies / lack of skils  | |
| resistance to change / mindset shift  | |
| | **Operating Model** |
| Idea - Plan - Build - measure | | 
  
</details>

<!--- END OF TOPIC--->

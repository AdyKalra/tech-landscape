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
 
**Legend:** ⭐⭐⭐-Significant ⭐⭐-Insightful ⭐-Good to know

<details>
<summary>🔧 Technical</summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |
| | **The Big Picture / Practices** |
| [High Level Design](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/High%20Level%20Design.md)| Overview of Client -> CDN / DNS -> LB -> Http Cache -> APIG -> XL -> Feature Services -> Core Services -> Domains |⭐⭐⭐ |
| [Stackshare tools](https://stackshare.io/categories) | All the best open source and Software as a Service (SaaS) tools in one place |⭐⭐ |
| | **Front-end Development Practice** |
| [Front-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | concepts - hoisting, event bubbling, scope prototype, shadow DOM. package managers - npm, yarn. CSS, BEM, Saas, Postcss.build tools - npm nuild, module bundlers webpack, linters and formatters, React Angualr Vue, modern css, css frameworks - reactstrap, mterialUI, Testing - Jest Cypress Mocha Chai. Progressive TypeScript, Server Side Rendering , GraphQL. ReactNative , Flutter , Static site generators  |⭐⭐⭐|
|[ReactJS](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/ReactJS.md)|open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components.|⭐⭐⭐|
| | **Back-end Development Practice** |
| [Back-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | C#, Java, Go, Python. Realational , NoSQL , Data Sharding , Replication , CAP. Authentication Oauth, token , JWT, SAML. apis - JSON, SOAP. Caching - DNS , serverside, clientside - Redis, MemCached. Design practices - GOF , DDD , TDD , SOLID, KISS , YAGNI, DRY. Architectural patterns - Microservices, SOA, Serverless. Messagebrokers , RabbitMQ , Kafka. Containers - Docker , GarphQL, Neo4j. |⭐⭐⭐|
|[NodeJs](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/NodeJs.md)| platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node. js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.|⭐⭐⭐|
| | **Generic Development Practice** |
|[Cloudformation](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/AWS%20Cloudformation.md)|Service that helps you model and set up your Amazon Web Services resources so that you can spend less time managing those resources and more time focusing on your applications that run in AWS.(JSON) or YAML standard.|⭐⭐⭐|
|[Lambda](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/AWS%20Lambda.md)|serverless compute service that runs your code in response to events and automatically manages the underlying compute resources for you. auto-scale (in & out) capability and their pay-per-use pricing model. dramatically less expensive than even the smallest EC2 instances.|⭐⭐⭐|
|[SQS and SNS](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/AWS%20SQS%20and%20SNS.md)|(SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications.(SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications|⭐⭐⭐|
|[Auto Scaling](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Auto%20Scaling.md)|AWS Auto Scaling monitors your applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost.scaling plans for Amazon EC2 instances and Spot Fleets, Amazon ECS tasks, Amazon DynamoDB tables and indexes, and Amazon Aurora Replicas.|⭐⭐|
|[BottleRocket](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/BottleRocket.md)|stripped-down version of Linux called Bottlerocket that has just enough code to keep the machine running.Teams running microservices can choose it and quit worrying about extra cruft like FTP servers sitting around in the background.|⭐|
|[Contentful](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Contentful.md)|Headless and decoupled solution for managing content.update the content of your website, a mobile app or any other platform that displays content.|⭐|
|[Datalake](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Datalake.md)|centralized repository that allows you to store all your structured and unstructured data at any scale. You can store your data as-is, without having to first structure the data, and run different types of analytics—from dashboards and visualizations to big data processing, real-time analytics, and machine learning to guide better decisions.Data Lakes compared to Data Warehouses|⭐⭐|
|[Dynamodb and Dynamodb streams](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Dynamodb%20and%20Dynamodb%20streams.md)|DynamoDB is a fully managed proprietary NoSQL database service that supports key-value and document data structures and is offered by Amazon. A DynamoDB stream is an ordered flow of information about changes to items in a DynamoDB table.Shards in DynamoDB streams are collections of stream records.|⭐⭐⭐|
|[Eventbridge](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Eventbridge.md)|Is a serverless event bus that makes it easy to connect applications together using data from your own applications, integrated Software-as-a-Service (SaaS) applications, and AWS services.|⭐⭐⭐|
|[GraphQL](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/GraphQL.md)|open-source data query and manipulation language for APIs. GraphQL is a syntax that describes how to ask for data, and is generally used to load data from a server to a client. GraphQL has three main characteristics: It lets the client specify exactly what data it needs. It makes it easier to aggregate data from multiple sources|⭐|
|[Jupyter](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Jupyter.md)|analytics notebooks. These are Mathematica-inspired applications that combine text, visualization and code in a living, computational document.|⭐|
|[Kafka](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Kafka.md)|distributed streaming platform that is used publish and subscribe to streams of records.Kafka offers much higher performance than message brokers like RabbitMQ.topics in Kafka are retention based: messages are retained for some configurable amount of time.|⭐⭐⭐|
|[Kinesis](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Kinesis.md)|Kinesis is a managed, scalable, cloud-based service that allows real-time processing of streaming large amount of data per second. ... It is used to capture, store, and process data from large, distributed streams such as event logs and social media feeds.|⭐⭐⭐|
|[Memcached](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Memcached.md)| general-purpose distributed memory-caching system. It is often used to speed up dynamic database-driven websites by caching data and objects in RAM to reduce the number of times an external data source must be read|⭐⭐⭐|
|[Opinionated and automated code formatting using pre commit hooks](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Opinionated%20and%20automated%20code%20formatting%20using%20pre%20commit%20hooks.md)|Prettier has been getting our vote for JavaScript, but similar tools, such as Black for Python, are available for many other languages and are increasingly being built-in as we see with Golang and Elixir.|⭐⭐⭐|
|[Redis MongoDB Postgres](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Redis%20MongoDB%20Postgres.md)|In-memory data structure project implementing a distributed, in-memory key-value database with optional durability.|⭐⭐⭐|
|[]()||⭐⭐⭐|
| | **Testing Practice** |
| [Testing Raodmap](https://github.com/anas-qa/Quality-Assurance-Road-Map) | Test Plan template, testing startegies, testing types, TDD , automation - mobile , web , API , contrct testing Packt, Testing Pyramid , Gap Analysis , Customer Insights , E2E regression suite |⭐⭐⭐|
| | **Mobile Development Practice** |
|[android roadmap](https://roadmap.sh/android) |Kotlin , Java |⭐⭐|
| | **DevOps / Cloud Platform Practice** |
| [Devops Roadmap](https://github.com/kamranahmedse/developer-roadmap) | Pytho, Ruby , NodeJS. initd, systemd. OS - Linus , FreeBSD. Terminal - maniupaltion tools,, BASH, vim, network. Protocosl - http, ftp, ssh. Reverseproxy, Caching server, Forward Proxy , Load balancer, firewall. Webserver - Nginx, Service Mesh - Istio. Containers, Config mgmt, container orchestration, Infra provisioning. CI/CD tools, Infra monitoring - Prometheus , Nagios, Grafana. Appln Monitoring - NewRelic , AppDynamics. Log Mgmt - Elastic stalk, splunk sumo. Cloud - AWS , GCP, Azure. Cloud Design Patterns - Availability , Data Management.  |⭐⭐⭐|  
|[API Gateway](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/AWS%20API%20Gateway.md)| reating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. server that is the single entry point into the system. ... The API Gateway is responsible for request routing, composition, and protocol translation. All requests from clients first go through the API Gateway. It then routes requests to the appropriate microservice / API Gateway Act as a Load Balancer|⭐⭐|
|[AWS Serverless Application Model (SAM)](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/AWS%20SAM.md)| open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines per resource, you can define the application you want and model it using YAML.AWS SAM templates are an extension of AWS CloudFormation templates|⭐⭐|
|[Buildkite](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Buildkite.md)|platform for running fast, secure, and scalable continuous integration pipelines on your own infrastructure|⭐|
|[Infrastructure Diagrams as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20Diagrams%20as%20Code.md)|Diagrams lets you draw the cloud system architecture using Python code and allows you to track the architecture diagram changes in any version control system.currently supports six major providers: AWS, Azure, GCP, Kubernetes, Alibaba Cloud and Oracle Cloud.|⭐|
|[Infrastructure as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20as%20Code.md)|Examples of infrastructure-as-code tools include AWS CloudFormation, Red Hat Ansible, Chef, Puppet, SaltStack and HashiCorp Terraform. Some tools rely on a domain-specific language (DSL), while others use a standard template format, such as YAML and JSON.|⭐⭐⭐|
|[Infrastructure configuration scanner](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20configuration%20scanner.md)|to ensure the configuration is safe and secure - open-source scanners such as prowler for AWS and kube-bench for Kubernetes|⭐⭐⭐|
|[Kubernetes ](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/K8s.md)|vendor-agnostic cluster and container management tool, open-sourced by Google, platform for automating deployment, scaling, and operations of application containers across clusters of hosts , Managed K8s|⭐⭐⭐|
|[Nginx](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Nginx.md)|web server which can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache. a reverse proxy is a type of proxy server that retrieves resources on behalf of a client from one or more servers. These resources are then returned to the client, appearing as if they originated from the proxy server itself.|⭐⭐|
|[Pipelines as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Pipelines%20as%20Code.md)|Emphasizes that the configuration of delivery pipelines that build, test and deploy our applications or infrastructure should be treated as code. LambdaCD, Drone, GoCD and Concourse are examples that allow usage of this technique.|⭐⭐⭐|
|[Secrets as a service](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Secrets%20as%20a%20service.md)|With this technique you can use tools such as Vault or AWS Key Management Service (KMS) to read/write secrets over an HTTPS endpoint with fine-grained levels of access control.Secrets as a service uses external identity providers such as AWS IAM to identify the actors who request access to secrets. |⭐|
|[Service mesh](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Service%20mesh.md)|approach to operating a secure, fast and reliable microservices ecosystem It has been an important stepping stone in making it easier to adopt microservices at scale.It offers discovery, security, tracing, monitoring and failure handling. It provides these cross-functional capabilities without the need for a shared asset such as an API gateway or baking libraries into each service.|⭐⭐⭐|
|[]()||⭐⭐⭐|
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
|[Datadog](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Datadog.md)|used by IT, operations, and development teams who build and operate applications that run on dynamic or hybrid cloud infrastructure.  Performance Monitoring category |⭐⭐|
|[Kibana and Logstash](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Kibana%20Logstash.md)|open source data visualization dashboard for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. The ELK Stack is a collection of three open-source products — Elasticsearch, Logstash, and Kibana|⭐⭐|
</details>

<!--- END OF TOPIC--->

<details>
<summary>📃 Process</summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |  
| | **Engineering Challenges** |
| Bug Bash | testing across verticals | ⭐⭐| 
| DevOps culture| transitioning from Devops to CPT  |⭐⭐⭐|  
| Web Modernisation| transitioning from legacy PHP to a SPA built on React and NodeJS (tiger team) |⭐⭐⭐|  
| Serverless | Going completely serverless | ⭐⭐⭐| 
| | **Change Management** |
| Champions  | lead mini transformations |⭐| 
| Design Patterns | building a repository of design patterns , BFF / XL , Domain driven design  | ⭐⭐| 
| | **Customer Insights** |
|  VOC , GA | working backwards from customer insights |⭐⭐|   
| | **Mission Team Experimentation** |
| | | 
| | **Visibility of Work in Value Stream** |
| | | 

</details>

<!--- END OF TOPIC--->

<details>
<summary>🔍 Measurement</summary> 
    
|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        | 
| | **Cloud Tools / Practices** |
|[cdk patterns](https://github.com/cdk-patterns/serverless) | SensibleDeafults for Patterns used - all of the official AWS Serverless architecture patterns built with CDK for developers to use |⭐⭐|  
| [cloudformation](https://github.com/aws-cloudformation/awesome-cloudformation) | cloud formation catalouge - A curated list of resources and projects for working with AWS CloudFormation. https://aws.amazon.com/cloudformation/ |⭐⭐⭐|  
| [Design Patterns](http://en.clouddesignpattern.org/index.php/Main_Page) | sensible defaults Design Patterns / catalouge - collection of solutions and design ideas for using AWS cloud technology to solve common systems design problems |⭐⭐|  
| [this-is-my-architecture](https://aws.amazon.com/this-is-my-architecture/?sc_channel=EL&sc_campaign=Explainer_2017_vid&sc_medium=YouTube&sc_content=video942&sc_detail=EXPLAINER&sc_country=US&tma.sort-by=item.additionalFields.airDate&tma.sort-order=desc) | Clarity of bigger picture within Org - Innovative cloud architectures from AWS partners and customers |⭐⭐|  
| | **Monitoring** |
|[Datadog](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Datadog.md)|used by IT, operations, and development teams who build and operate applications that run on dynamic or hybrid cloud infrastructure.  Performance Monitoring category |⭐⭐|
| | **Proactive failiure notification** |
| | |
| | **Engineering efficiency** |
| STAX / Cloud Confirmity | cloud compliance and measuring where we are , cost  | ⭐⭐|  
| Well architected framework | Cloud maturity and assesment | 
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making | ⭐⭐|  

</details>

<!--- END OF TOPIC--->

<details>
<summary>🤝‍ Cultural  </summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |   
| | **Recruitment** |   |
| | **Reviews and evaluate work** |  
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making |⭐⭐|  
| Westrum Organisation Culture ||⭐⭐⭐|  
| | **Learning Culture** |
| | |

</details>

<!--- END OF TOPIC--->

<details>
<summary> 💡 Strategic </summary>

|  Name |  Summary |Ratings |
|:-:    |:-:       |:-:        | 
| | **Engineering Ideas / Techniques ** |
| [engineering roadmaps](https://roadmap.sh/) | all Reference Roadmaps - roadmaps on web | ⭐⭐⭐|  
| [Google Engineering practices](https://github.com/google/eng-practices) | Sensible Deafults template for practices - Google has many generalized engineering practices that cover all languages and all projects. These documents represent the collective experience of various best practices that we have developed over time. |⭐⭐|  
| Four key metrics | MMTR , Lead Time , Deployment frequency and Change fail rate - Measure engineering team health | ⭐⭐⭐|  
| Gitprime for data driven mindset | Coding Days , Impact , Efficiency , Commits per day , Repos - Data driven engineering metrics | ⭐⭐⭐|  
| Technology Radar | Internal tooling maturity | ⭐⭐⭐|  
| Engineering maturity assessment | 12 factor app - measure engineering maturity every quarter |⭐⭐⭐|  
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

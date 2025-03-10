Tech Cheatsheet - Snapshot view of everything tech - tools , techniques , Cloud , Bigger Picture

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
<summary>🔧 Technical - Big Picture | Front-end | Back-end | Generic Dev | Testing  | Mobile Dev | Devops/Cloud Platfrom | Architecture | Ops </summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |
| | **The Big Picture tech/ Practices** |
| [High Level Design](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/High%20Level%20Design%20-%20Big%20Picture.md)| Overview of Client -> CDN / DNS -> LB -> Http Cache -> APIG -> XL -> Feature Services -> Core Services -> Domains |⭐⭐⭐ |
|[CDN Incapsula Akamai Cloudfront](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/CDN%20Incapsula%20Akamai%20Cloudfront.md)|(CDN) refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content. A CDN allows for the quick transfer of assets needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.|⭐⭐⭐|
|[API Gateway - NGINX, Kong, Tyk, Ambassador, AWS API gateway](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/AWS%20API%20Gateway.md)| Creating, publishing, maintaining, monitoring, and securing REST, HTTP, and WebSocket APIs at any scale. server that is the single entry point into the system. ... The API Gateway is responsible for request routing, composition, and protocol translation. All requests from clients first go through the API Gateway. It then routes requests to the appropriate microservice / API Gateway Act as a Load Balancer|⭐⭐⭐|
|[CI](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Orchestrating%20CI%20CD%20Pipelines.md)|Continuous Integration (CI) is a development practice that requires developers to integrate code into a shared repository several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early.Continuous Integration doesn’t get rid of bugs, but it does make them dramatically easier to find and remove.|⭐|
|[Coordinating pull requests and code reviews in Slack](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Coordinating%20pull%20requests%20and%20code%20reviews%20in%20Slack.md)|Modern software development often requires large teams of people interacting over a single codebase, using code tracking systems that can manage incoming and outgoing changes while avoiding conflicts. While every engineering team might use a different service to manage their code, they can all use Slack as the central place for testing and review.Using a combination of channels, threads and apps, engineering teams can save a lot of time by not needing to wade through email inboxes and app alerts, or jump between browser tabs. And that means their code gets into customers’ hands that much faster.|⭐⭐⭐|
|[Code Deployment best practices from Slack](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Code%20Deployment%20best%20practices.md)|At Slack, we value quick iteration, fast feedback loops, and responsiveness to customer feedback. We also have hundreds of engineers who are trying to be as productive as possible. Keeping to these values while growing as a company means continual refinement of our deployment system. We had to invest in greater visibility and reliability in order to accommodate the amount of work being done. This post will outline our process and a few of the major projects that got us to where we are.|⭐⭐⭐|
|[Coordinating code deploys and continuous integration in Slack](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Coordinating%20code%20deploys%20and%20continuous%20integration%20in%20Slack.md)|Software development at large organizations often entails dozens, even hundreds, of programmers working concurrently on millions of lines of code. Their success, however, is measured by a more precise metric: how quickly they can get what they build into their customers’ hands.Slack is a powerful addition to the toolchain of apps required to properly test, document and deploy code. It acts as a discussion space to foster collaboration and help support the efforts of engineering teams but also as a centralized, long-term record of what’s taken place, which includes most of the other apps your team may use.Here at Slack, we deploy dozens of code changes to production servers multiple times a day. To get the granular details of our in-house process, check out our post on Code Deploys|⭐⭐⭐|
| [Stackshare tools](https://stackshare.io/categories) | All the best open source and Software as a Service (SaaS) tools in one place |⭐ |
|[Scaling Microservices](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Scaling%20Microservices.md)|Use a container-based pipeline,Consolidate to a single pipeline that operates with context,Adopt canary release testing|⭐⭐|
|[Serverless](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Serverless.md)|The term 'serverless' is somewhat misleading, as there are still servers providing these backend services, but all of the server space and infrastructure concerns are handled by the vendor. Serverless means that the developers can do their work without having to worry about servers at all. - managed services|⭐⭐⭐|
|[Real World Scenarios - Serverless](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Scaling%20Serverless%20Applications.md)|org examples|⭐⭐⭐|
| | **Architecture Practice** |
|[system-design-notebook](https://github.com/bregman-arie/system-design-notebook)|Learn System Design step by step|⭐⭐⭐|
|[Scalable-Software-Architecture](https://github.com/Developer-Y/Scalable-Software-Architecture)|Collection of tech talks, papers and web links on Distributed Systems, Scalability and System Design.|⭐⭐⭐|
|  [awesome-software-architect-roadmap](https://github.com/AlaaAttya/software-architect-roadmap) | View roadmaps about architect roles to help you learn |⭐⭐⭐|
|  [awesome-software-design-and-architecture-roadmap](https://github.com/stemmlerjs/software-design-and-architecture-roadmap) | The software design and architecture roadmap for any developer https://solidbook.io |⭐⭐⭐|
|[data-oriented-design](https://github.com/dbartolini/data-oriented-design)|A curated list of data oriented design resources.|⭐⭐|
|[system-design-primer](https://github.com/donnemartin/system-design-primer)|Learn how to design large-scale systems.|⭐⭐⭐|
|[awesome-scalability](https://github.com/binhnguyennus/awesome-scalability)|The Patterns of Scalable, Reliable, and Performant Large-Scale Systems http://awesome-scalability.com/|⭐⭐|
|[system-design-in-practice](https://github.com/resumejob/system-design-in-practice)|Learn how to design a system from tech company blogs - real world examples|⭐⭐|
|[awesome-software-architecture-web](https://mehdihadeli.github.io/awesome-software-architecture/)|A curated list of awesome articles and resources to learn and practice about software architecture, patterns, and principles.|⭐⭐⭐|
|[System Design Blueprint / Cheatsheet](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/System%20Design%20Blueprint%20-%20Cheatsheet.md)|visual guide that provides developers with a quick and easy reference to key concepts and best practices in system design.|⭐⭐⭐|

| | **Front-end Development Practice** |
| [Front-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | concepts - hoisting, event bubbling, scope prototype, shadow DOM. package managers - npm, yarn. CSS, BEM, Saas, Postcss.build tools - npm nuild, module bundlers webpack, linters and formatters, React Angualr Vue, modern css, css frameworks - reactstrap, mterialUI, Testing - Jest Cypress Mocha Chai. Progressive TypeScript, Server Side Rendering , GraphQL. ReactNative , Flutter , Static site generators  |⭐⭐⭐|
|[ReactJS](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/ReactJS.md)|open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components.|⭐⭐⭐|
|[Introducing and Scaling a GraphQL BFF](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Introducing%20and%20Scaling%20a%20GraphQL%20BFF.md)|Journey of introducing and then scaling a GraphQL BFF to serve multiple applications.Covers the benefits of the Backend For Frontend pattern and why it's a popular way to introduce GraphQL.how to remain agile and support a production application throughout this process.|⭐⭐|
| | **Back-end Development Practice** |
| [Back-end Roadmap](https://github.com/kamranahmedse/developer-roadmap) | C#, Java, Go, Python. Realational , NoSQL , Data Sharding , Replication , CAP. Authentication Oauth, token , JWT, SAML. apis - JSON, SOAP. Caching - DNS , serverside, clientside - Redis, MemCached. Design practices - GOF , DDD , TDD , SOLID, KISS , YAGNI, DRY. Architectural patterns - Microservices, SOA, Serverless. Messagebrokers , RabbitMQ , Kafka. Containers - Docker , GarphQL, Neo4j. |⭐⭐⭐|
|[NodeJs](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/NodeJs.md)| platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node. js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.|⭐⭐⭐|
|[Gold Stack](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/GoLD%20Stack.md)|GoLang + Lambda + DynamoDB|⭐|
| | **Generic Development Practice** |
|[FullStack](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/FullStack.md)|what does a full stack need in an interview|⭐⭐⭐|
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
|[Redis MongoDB Postgres](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Redis%20MongoDB%20Postgres.md)|In-memory data structure project implementing a distributed, in-memory key-value database with optional durability.PostgreSQL is a free and open-source relational database management system (RDBMS) emphasizing extensibility and SQL compliance. |⭐⭐⭐|
|[]()||⭐⭐⭐|
| | **Testing Practice** |
|[Component Visual Regression Testing](https://github.com/AdyKalra/technolgytrends/blob/master/Testing%20trends/Component%20Visual%20Regression%20Testing.md)|good balance between value and cost to ensure that no undesired visuals have been added to the application|⭐⭐|
| [Testing Raodmap](https://github.com/anas-qa/Quality-Assurance-Road-Map) | Test Plan template, testing startegies, testing types, TDD , automation - mobile , web , API , contrct testing Packt, Testing Pyramid , Gap Analysis , Customer Insights , E2E regression suite |⭐⭐⭐|
|[Cypress and Puppeteer](https://github.com/AdyKalra/technolgytrends/blob/master/Testing%20trends/Cypress%20and%20Puppeteer.md)|JavaScript End to End Testing Framework|⭐⭐⭐|
|[LocalStack](https://github.com/AdyKalra/technolgytrends/blob/master/Testing%20trends/LocalStack.md)|LocalStack solves this problem for AWS by providing local test double implementations of a wide range of AWS services including S3, Kinesis, DynamoDB and Lambda.|⭐⭐⭐|
|[Scaling Automated Tests Beyond a Single Project](https://github.com/AdyKalra/technolgytrends/blob/master/Testing%20trends/Scaling%20Automated%20Tests%20Beyond%20a%20Single%20Project.md)|How to increase the ROI of your automated tests by using test frameworks with a highly readable DSL and reusable components|⭐⭐⭐|
| | **Mobile Development Practice** |
|[android roadmap](https://roadmap.sh/android) |Kotlin , Java |⭐⭐|
| | **DevOps / Cloud Platform Practice** |
|[services-engineering](https://github.com/mmcgrana/services-engineering)|A reading list for services engineering, with a focus on cloud infrastructure services|⭐⭐⭐|
|[DevOps-Guide](https://github.com/Tikam02/DevOps-Guide)|DevOps Guide - Development to Production all configurations with basic notes to debug efficiently.|⭐⭐⭐|
| [Devops Roadmap](https://github.com/kamranahmedse/developer-roadmap) | Pytho, Ruby , NodeJS. initd, systemd. OS - Linus , FreeBSD. Terminal - maniupaltion tools,, BASH, vim, network. Protocosl - http, ftp, ssh. Reverseproxy, Caching server, Forward Proxy , Load balancer, firewall. Webserver - Nginx, Service Mesh - Istio. Containers, Config mgmt, container orchestration, Infra provisioning. CI/CD tools, Infra monitoring - Prometheus , Nagios, Grafana. Appln Monitoring - NewRelic , AppDynamics. Log Mgmt - Elastic stalk, splunk sumo. Cloud - AWS , GCP, Azure. Cloud Design Patterns - Availability , Data Management.  |⭐⭐⭐|
|[devops-resources](https://github.com/bregman-arie/devops-resources)|Useful resources and information regarding DevOps and secondly, provide some roadmap for those who want to practice DevOps.|⭐⭐|
|[devops-exercises](https://github.com/bregman-arie/devops-exercises)|Questions and exercises on various technical topics, sometimes related to DevOps and SRE.|⭐⭐|
|[AWS Serverless Application Model (SAM)](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/AWS%20SAM.md)| open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines per resource, you can define the application you want and model it using YAML.AWS SAM templates are an extension of AWS CloudFormation templates|⭐⭐|
|[Buildkite](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Buildkite.md)|platform for running fast, secure, and scalable continuous integration pipelines on your own infrastructure|⭐|
|[Infrastructure Diagrams as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20Diagrams%20as%20Code.md)|Diagrams lets you draw the cloud system architecture using Python code and allows you to track the architecture diagram changes in any version control system.currently supports six major providers: AWS, Azure, GCP, Kubernetes, Alibaba Cloud and Oracle Cloud.|⭐|
|[Infrastructure as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20as%20Code.md)|Examples of infrastructure-as-code tools include AWS CloudFormation, Red Hat Ansible, Chef, Puppet, SaltStack and HashiCorp Terraform. Some tools rely on a domain-specific language (DSL), while others use a standard template format, such as YAML and JSON.|⭐⭐⭐|
|[Infrastructure configuration scanner](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20configuration%20scanner.md)|to ensure the configuration is safe and secure - open-source scanners such as prowler for AWS and kube-bench for Kubernetes|⭐⭐⭐|
|[Kubernetes ](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/K8s-Kubernetes.md)|vendor-agnostic cluster and container management tool, open-sourced by Google, platform for automating deployment, scaling, and operations of application containers across clusters of hosts , Managed K8s|⭐⭐⭐|
|[Nginx](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Nginx.md)|web server which can also be used as a reverse proxy, load balancer, mail proxy and HTTP cache. a reverse proxy is a type of proxy server that retrieves resources on behalf of a client from one or more servers. These resources are then returned to the client, appearing as if they originated from the proxy server itself.|⭐⭐|
|[Pipelines as Code](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Pipelines%20as%20Code.md)|Emphasizes that the configuration of delivery pipelines that build, test and deploy our applications or infrastructure should be treated as code. LambdaCD, Drone, GoCD and Concourse are examples that allow usage of this technique.|⭐⭐⭐|
|[Secrets as a service](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Secrets%20as%20a%20service.md)|With this technique you can use tools such as Vault or AWS Key Management Service (KMS) to read/write secrets over an HTTPS endpoint with fine-grained levels of access control.Secrets as a service uses external identity providers such as AWS IAM to identify the actors who request access to secrets. |⭐|
|[Service mesh](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Service%20mesh.md)|approach to operating a secure, fast and reliable microservices ecosystem It has been an important stepping stone in making it easier to adopt microservices at scale.It offers discovery, security, tracing, monitoring and failure handling. It provides these cross-functional capabilities without the need for a shared asset such as an API gateway or baking libraries into each service.|⭐⭐⭐|
|[Infrastructure Automation Maturity Model](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Infrastructure%20Automation%20Maturity%20Model.md)| four questions that can quickly assess the state of infrastructure automation within an organization.|⭐⭐|
|[]()||⭐⭐⭐|
| | **Architecture Practice** |
|[Organising Architecture](https://github.com/AdyKalra/technolgytrends/blob/master/Architecture%20trends/Organising%20Architecture.md)||⭐⭐|
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
|[Splunk](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Splunk.md)| searching, monitoring, and examining machine-generated Big Data through a web-style interface. Splunk performs capturing, indexing, and correlating the real-time data in a searchable container from which it can produce graphs, reports, alerts, dashboards, and visualizations.|⭐⭐⭐|
|[DevOps v/s SRE](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/DevOps%20Versus%20SRE.md)|Decoupling DevOps and RunOps — The Genesis of Site Reliability Engineering (SRE)|⭐|
|[Grafana On-Call](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/Grafana%20On%20Call.md)|On Call from Pager Duty to Grafana|⭐| 
|[DoD Enterprise DevSecOps Reference Design](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/DoD%20Enterprise%20DevSecOps%20Reference%20Design.md)|The benefits of adopting DevSecOps include:Mean-time to production: the average time it takes from when new software features are required until they are running in production.Lead Time Average lead-time: how long it takes for a new requirement to be delivered and deployed.Deployment speed: how fast a new version of the application can be deployed into the production environment.
|Four Key Metrics| Deployment frequency: how often a new release can be deployed into the production environment.Change Fail Rate Production failure rate: how often software fails during production.MTTR Mean-time to recovery: how long it takes applications in the production stage to recover from failure.|⭐⭐⭐|
|[Chaos Engineering](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/Chaos%20Engineering.md)|creating failures and outages in a controlled environment. accepted, mainstream approach to improving and assuring distributed system resilience. As organizations large and small begin to implement Chaos Engineering as an operational process, we're learning how to apply these techniques safely at scale.|⭐⭐|
|[Setting SLOs](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/Setting%20SLOs.md)|If you follow site reliability engineering (SRE) principles, you can measure customer experience with service-level objectives (SLOs). SLOs allow you to quantifiably measure customer happiness, which directly impacts the business. Instead of creating a potentially unbounded number of monitoring metrics, we suggest using a small number of alerts grounded in customer pain—i.e., violation of SLOs. This lets you focus alerts on scenarios where you can confidently assert that customers are experiencing, or will soon experience, significant pain.|⭐⭐⭐|
|[Application Monitoring Simplified](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/application%20monitoring%20simplified.md)|How Netflix built TellTale|
</details>

<!--- END OF TOPIC--->

<details>
<summary>📃 Process - Change Management | Customer Insights | Visibility of Work in Value Stream | Mission Team Experimentation </summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |  
| | **Change Management** |
| Champions  | lead mini transformations |⭐| 
|[the-engineering-managers-booklist](https://github.com/jesselpalmer/the-engineering-managers-booklist)|Books for people who are or aspire to manage/lead team(s) of software engineers|⭐⭐⭐| 
| Design Patterns | building a repository of design patterns , BFF / XL , Domain driven design  | ⭐⭐| 
| | **Customer Insights** |
|  VOC , GA | working backwards from customer insights |⭐⭐|   
| | **Mission Team Experimentation** |
| | | 
| | **Visibility of Work in Value Stream** |
|[Path-to-production Mapping](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Path-to-production%20mapping.md) | aPth-to-production mapping has been a near-universal practice since codifying Continuous Delivery, eyeopener and easiest way to discover areas of CI|⭐⭐⭐| 
| | | 

</details>

<!--- END OF TOPIC--->

<details>
<summary>🔍 Measurement - Cloud Tools for Practices / Sensibe Deafults | Monitoring | Engineering efficiency </summary> 
    
|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        | 
| | **Cloud Tools for Practices / Compliance / Sensibe Deafults** |
| STAX / Cloud Confirmity | cloud compliance and measuring where we are , cost  | ⭐⭐⭐|  
| Well architected framework | Cloud maturity and assesment | ⭐⭐⭐|  
|[AWS Analytics Lens](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Analytics%20Lens.md)|The new Analytics Lens offers comprehensive guidance to make sure that your analytics applications are designed in accordance with AWS best practices. The goal is to give you a consistent way to design and evaluate cloud architectures, based on the following five pillars of the well architected framework:Operational excellence,Security,Reliability,Performance efficiency,Cost optimization|⭐⭐| 
|[cdk patterns](https://github.com/cdk-patterns/serverless) | SensibleDeafults for Patterns used - all of the official AWS Serverless architecture patterns built with CDK for developers to use |⭐⭐|  
| [cloudformation](https://github.com/aws-cloudformation/awesome-cloudformation) | cloud formation catalouge - A curated list of resources and projects for working with AWS CloudFormation. https://aws.amazon.com/cloudformation/ |⭐⭐⭐|  
| [Design Patterns](http://en.clouddesignpattern.org/index.php/Main_Page) | sensible defaults Design Patterns / catalouge - collection of solutions and design ideas for using AWS cloud technology to solve common systems design problems |⭐⭐|  
| [this-is-my-architecture](https://aws.amazon.com/this-is-my-architecture/?sc_channel=EL&sc_campaign=Explainer_2017_vid&sc_medium=YouTube&sc_content=video942&sc_detail=EXPLAINER&sc_country=US&tma.sort-by=item.additionalFields.airDate&tma.sort-order=desc) | Clarity of bigger picture within Org - Innovative cloud architectures from AWS partners and customers |⭐⭐|  
| | **Monitoring / Proactive failiure notification** |
|[Datadog](https://github.com/AdyKalra/technolgytrends/blob/master/CloudPlatform%20trends/Datadog.md)|used by IT, operations, and development teams who build and operate applications that run on dynamic or hybrid cloud infrastructure.  Performance Monitoring category |⭐⭐|
|[Kibana and Logstash](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Kibana%20Logstash.md)|open source data visualization dashboard for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. The ELK Stack is a collection of three open-source products — Elasticsearch, Logstash, and Kibana|⭐⭐|
|[Splunk](https://github.com/AdyKalra/technolgytrends/blob/master/Development%20trends/Splunk.md)| searching, monitoring, and examining machine-generated Big Data through a web-style interface. Splunk performs capturing, indexing, and correlating the real-time data in a searchable container from which it can produce graphs, reports, alerts, dashboards, and visualizations.|⭐⭐⭐|
|[Distributed Monitoring 101: the “Four Golden Signals”](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Four%20Golden%20Signals.md)|In monitoring distributed systems, Google’s SRE book outlines the four golden signals of monitoring as LETS - Latency, Errors, Traffic, and Saturation.|⭐⭐⭐|
|[Application Monitoring Simplified](https://github.com/AdyKalra/technolgytrends/blob/master/PostProduction%20trends/application%20monitoring%20simplified.md)|How Netflix built TellTale|
| | **Engineering efficiency** |
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making | ⭐⭐|  
|[Data Driven Engineering](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Data%20Driven%20Engineering.md)|Data helps IT leaders visualize how work is being done, the quality and quantity of output, and how they can improve the lives of staff.|⭐⭐| 
|[Dev Productivity Metrics](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Dev%20Productivity%20Metrics.md)| Developer Productivity Metrics at tech companies|⭐⭐⭐|

</details>

<!--- END OF TOPIC--->

<details>
<summary>🤝‍ Cultural - Recruitment | Learning | Leadership | Tech Blog | </summary>

|  Name |  Summary |   Ratings |
|:-:    |:-:       |:-:        |   
| | **Recruitment** |   |
|[awesome-AI-ML-talent-management](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/awesome-AI_ML_Talent_Mangement.md)|ai in talent mgmnt research|⭐⭐| 
|[engineeringladders](https://github.com/jorgef/engineeringladders)|A framework for Engineering Managers - roles explained|⭐⭐| 
|[manager-resources](https://github.com/VGraupera/manager-resources)|A curated list of resources for front-line engineering managers|⭐⭐|
| | **Reviews and evaluate work** |  
| [patterns in teams and ICs](https://www.pluralsight.com/product/flow/20-patterns)| 20 patterns to watch for in your engineering team - teams and IC patterns tools like flow and decision making |⭐⭐|  
| Westrum Organisation Culture ||⭐⭐⭐|  
| | **Learning Culture** |
|[launch company tech blog](https://www.welcometothejungle.com/en/articles/company-blog-tech)|considerations before launching a company tech blog|⭐⭐|
|[]()||⭐⭐⭐| 
| | **Leadership** |
|  [awesome-leading-and-managing](https://github.com/LappleApple/awesome-leading-and-managing) | Awesome List of resources on leading people and being a manager. Geared toward tech, but potentially useful to anyone. |⭐⭐⭐| 
|[Managers Playbook](https://github.com/ksindi/managers-playbook)|Heuristics for effective management.|⭐⭐⭐|
|[Engineering Management](https://github.com/charlax/engineering-management)|A collection of inspiring resources related to engineering management and tech leadership|⭐⭐⭐|
|[digital-transformation-leadership-manifesto](https://enterprisersproject.com/article/2020/7/digital-transformation-leadership-manifesto)|A manifesto for moving from good manager to true IT leader|⭐|
|[engineering-management-resources](https://github.com/afternoon/engineering-management-resources)|A list of resources for engineering managers of all levels|⭐⭐|
| [Digital transformation: 8 ways to spot your organization's rising leaders](https://enterprisersproject.com/article/2020/7/digital-transformation-rising-leaders)| Pointers on leadership in DT|
</details>

<!--- END OF TOPIC--->

<details>
<summary> 💡 Strategic - Engineering Techniques | Operating Model </summary>

|  Name |  Summary |Ratings |
|:-:    |:-:       |:-:        | 
| | **Engineering Techniques - Big Picture** |
| [engineering roadmaps](https://roadmap.sh/) | all Reference Roadmaps - roadmaps on web | ⭐⭐⭐| 
| Bug Bash | testing across verticals | ⭐⭐| 
| DevOps culture| transitioning from Devops to CPT  |⭐⭐⭐|  
|[services-engineering](https://github.com/mmcgrana/services-engineering)|A reading list for services engineering, with a focus on cloud infrastructure services|⭐⭐⭐|
| Web Modernisation| transitioning from legacy PHP to a SPA built on React and NodeJS (tiger team) |⭐⭐⭐|  
| Serverless | Going completely serverless | ⭐⭐⭐| 
|[awesome-talks](https://github.com/JanVanRyswyck/awesome-talks)|tech online talks and screencasts|⭐⭐| 
|[Adaptive IT: Transformational framework](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Adaptive%20IT:%20Transformational%20framework.md)|five pillars of the adaptive IT framework and thier measures.|⭐⭐⭐|
|[Auxiliary Engineering](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Auxillary%20Engineering.md)|Partnering with engineering teams to increase their velocity and build a lasting culture of quality.” We travel from team to team, embedding for enough time to help developers build habits as they build an MVP.|⭐⭐| 
| [Google Engineering practices](https://github.com/google/eng-practices) | Sensible Deafults template for practices - Google has many generalized engineering practices that cover all languages and all projects. These documents represent the collective experience of various best practices that we have developed over time. |⭐⭐|  
| [Four key metrics](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Four%20Key%20Metrics.md) | MMTR , Lead Time , Deployment frequency and Change fail rate - Measure engineering team health | ⭐⭐⭐|  
| Gitprime for data driven mindset | Coding Days , Impact , Efficiency , Commits per day , Repos - Data driven engineering metrics | ⭐⭐⭐|  
| Technology Radar | Internal tooling maturity | ⭐⭐⭐|  
| Engineering maturity assessment | 12 factor app - measure engineering maturity every quarter |⭐⭐⭐|  
|[Five things all execs should know about technology](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/01%20Five%20things%20all%20execs%20should%20know%20about%20technology.md)|Technology excellence matters, Digital talent is your key to success, Invest in continuous delivery & DevOps to deliver customer value faster., Building digital platforms, Moving from project to product thinking|⭐|  
|[APIs as Digital Factories](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/APIs%20as%20Digital%20Factories.md)|Don’t use technologies (and apis) to create new digital business. Build your software to upgrade YOUR business competitive edge for all customers, all employees, all brands, all channels…|⭐| 
|[How to measure – and manage – technical debt](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/measure%20and%20manage%20technical%20debt.md)|Technical debt, a term first coined by Ward Cunningham, is not unlike financial debt: It refers to the practice of making coding or design decisions to expedite production or gain other short-term benefits, knowing that these decisions may require corrections later.|⭐⭐⭐|
| | **Transformation Challenges** |
|[Adaptive IT: Transformational framework](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Adaptive%20IT:%20Transformational%20framework.md)|five pillars of the adaptive IT framework and thier measures.|⭐⭐⭐|
|[Digital transformation: 3 eye-opening tests to gauge customer focus](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Digital%20transformation%20-%20tests%20to%20gauge%20customer%20focus.md)|90-Minute IT Leadership Challenge, IT Roadmap Review, The Heartburn Test |⭐⭐|
|[20 patterns to watch for in your engineering team](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/20%20patterns%20to%20watch%20for%20in%20your%20engineering%20team.md)|Effective managers view their teams as complex interdependent systems, with inputs and outputs.When the outputs aren’t as expected, great managers approach the problem with curiosity and are relentless in their pursuit of the root cause. They watch code reviews and visualize work patterns, spotting bottlenecks or process issues that, when cleared, increase the overall health and capacity of the team.By searching for “why,” they uncover organizational issues and learn how their teams work and how to re how to resolve these problems in the future.20 patterns is a collection of work patterns we’ve observed in working with hundreds of software teams.|⭐⭐| 
| Lack of expertise and exposure |  | 
| pushback from people and existing leaders | |
| missing the overarching strategy across all business units in Digital | |
| new technologies / lack of skils  | |
| resistance to change / mindset shift  | |
| | **Operating Model** |
| Idea - Plan - Build - measure | | 
|[Adaptive IT: Transformational framework](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Adaptive%20IT:%20Transformational%20framework.md)|five pillars of the adaptive IT framework and thier measures.|⭐⭐⭐| 
|[DORA's research program](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/DORA's%20research%20program.md)|guide to DevOps, along with six years of State of DevOps Reports|⭐⭐⭐|
|[Developer-Effectiveness](https://github.com/AdyKalra/technolgytrends/blob/master/EngineeringPractices%20trends/Developer-Effectiveness.md)|Increase dev productivity|⭐⭐| 
|[DeScaling Organisation](https://github.com/AdyKalra/technolgytrends/blob/master/TechStrategy%20trends/DeScaling%20Organisation.md)|Maximum Meeting Size (MMS), Minimum Feedback Frequency (MFF) and Delegation/Collaboration Ratio (DCR).|⭐⭐⭐| 
|[Platform Engineering](https://github.com/AdyKalra/technolgytrends/blob/master/TechStrategy%20trends/Platform%20Engineering.md)|TSOC [Time Spent Outside Code]empowers software developers to focus on their work rather than the systems needed to do their work|⭐⭐⭐| 
|[Scaling Engineering](https://github.com/AdyKalra/technolgytrends/blob/master/TechStrategy%20trends/Scaling%20Engineering.md)|Ideas from Github/Microsoft/Google|⭐⭐⭐| 
|[]()||⭐⭐⭐| 
|[]()||⭐⭐⭐| 
  
</details>

<!--- END OF TOPIC--->

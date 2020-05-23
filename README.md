# Tech Landscape
## 📚 Table of Contents


### 🔧 Tools
<details>
<summary>View Snapshot</summary>

#### Development
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |  
| | | []() | **** **** **** |
| | | []() | **** **** **** |


#### Testing
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |  
| | | []() | **** **** **** |
| | | []() | **** **** **** |

#### Infrastructure
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |  
| | | []() | **** **** **** |
| | | []() | **** **** **** |

</details>

### 📃 Techniques
<details>
<summary>View Snapshot</summary>
  
#### Design Patterns
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |  
| | | []() | **** **** **** |
| | | []() | **** **** **** |

</details>

### 🌐 Cloud
<details>
<summary>View Snapshot</summary>
  
#### [AWS](https://aws.amazon.com/products/) 

##### Compute
|  Name |  Summary | Details  |   
|:-:    |:-:       |:-:       |
| EC2 	            | Virtual Servers in the cloud	                         | [EC2](https://aws.amazon.com/ec2/?c=7&pt=1)             |
| EC2 Autoscaling 	| Scale compute capacity to meet demand	                 | [EC2](https://aws.amazon.com/ec2/autoscaling/?c=7&pt=2) |
| Lambda 	          | Function as a Service - run your code in reponse to events	| [Lambda](https://aws.amazon.com/lambda/?c=7&pt=10) |
| Elastic Beanstalk | Run and manage web apps                  |[Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/?c=7&pt=8) |
| Outposts 	        | Run AWS services on prem	                             | [Outposts](https://aws.amazon.com/outposts/?c=7&pt=11)  |
| Serverless Application Repository| Discover Deploy and Publish Serverless applications|[SAR](https://aws.amazon.com/serverless/serverlessrepo/)|
| Batch 	          | Run batch jobs at any scale	                           | [Batch](https://aws.amazon.com/batch/?c=7&pt=7)         |

##### Analytics
|  Name |  Summary | Details  |   
|:-:    |:-:       |:-:       |
| Athena 	          | Query data in S3 using SQL	                           | [Athena](https://aws.amazon.com/athena/?c=1&pt=1)       |
| CloudSearch 	    | Managed search service	                           | [CloudSearch](https://aws.amazon.com/cloudsearch/?c=1&pt=2) |
| Elasticsearch Service| Fully managed and scalable ES with built-in Kibana	| [Elasticsearch](https://aws.amazon.com/elasticsearch-service/?c=1&pt=3) |
| Kinesis | Easily collect, process, and analyze video and data streams in real time |[Kinesis](https://aws.amazon.com/kinesis/?c=1&pt=5) |
| Kinesis Video Streams | Capture, process, and store media streams for playback, analytics, and machine learning	                             | [Video Streams](https://aws.amazon.com/kinesis/video-streams/)  |
| Kinesis Data Streams| Manually managed - Collect streaming data, at scale, for real-time analytics | [Streams](https://aws.amazon.com/kinesis/data-streams/)  |
| Kinesis Data Firehose | Fully Managed - Prepare and load real-time data streams into load streaming data into data lakes, data stores and analytics tools. Use Kinesis Streams if you want to do some custom processing with streaming data. With Kinesis Firehose you are simply ingesting it into S3, Redshift or ElasticSearch| [Firehose](https://aws.amazon.com/kinesis/data-firehose/)  |
| Kinesis Data Analytics | analyze streaming data, gain actionable insights | [Analytics](https://aws.amazon.com/kinesis/data-analyticsAnalytics/)  |
| Managed Kafka(MSK) | Fully managed, highly available, and secure Apache Kafka service | [MSK](https://aws.amazon.com/msk/?c=1&pt=6) |
| Redshift 	        | The most popular and fastest cloud data warehouse	for BI / Operational analytics| [Redshift](https://aws.amazon.com/redshift/?c=1&pt=7)|
| Data Pipeline | Orchestration service for data movement.           | [Data Pipeline](https://aws.amazon.com/datapipeline/?c=1&pt=10)|
| Glue 	        | ETL - Prepare and load data. Discovers your data and stores the associated metadata (e.g. table definition and schema) in the AWS Glue Data Catalog. Once cataloged, your data is immediately searchable, queryable, and available for ETL.| [Glue](https://aws.amazon.com/glue/?c=1&pt=11)  |
| Lake Formation | Identify existing data stores in S3 or relational and NoSQL databases, and move the data into your data lake.        | [Lake Formation](https://aws.amazon.com/lake-formation/?c=1&pt=12)  |

##### Application Integration
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |
| Step Functions | Build distributed applications using visual workflows | [Step Functions](https://aws.amazon.com/step-functions/?c=2&pt=1)  | **Data processing** - multiple ETL jobs execute in order, **Automate tasks** - routine deployments, upgrades, installations, and migrations, **recurring tasks** such as patch management, infrastructure selection, and data synchronization. , **Modernize a monolith** - carve off a few tasks from the rest of your codebase into microservices. **Application orchestration** - ombine multiple AWS Lambda functions into responsive serverless applications and microservices
| AppFlow  | Integrate Saas apps like Salesforce, Marketo, Slack, and ServiceNow, and AWS services like Amazon S3 and Amazon Redshift, and automate data flows , **without code** | [AppFlow](https://aws.amazon.com/appflow/?c=2&pt=2a)  | **Store or sync Salesforce data** **Hydrate data lakes** - send Dynatrace insights on application performance to a data lake **Routinely analyze events** create a data flow that sends event and conversation data from a Slack Channel to an Amazon Redshift or Snowflake data warehouse for downstream analysis. **Create routine reports of Datadog metrics** **Automate data back ups** - send high severity Zendesk tickets to Amazon S3 for further analysis|
| EventBridge| Serverless event bus that connects application data from your own apps, SaaS, and AWS services| [EventBridge](https://aws.amazon.com/eventbridge/?c=2&pt=2)  | **Customer support** - send status changes in customer support tickets to EventBridge and trigger an automated workflow **Security operations** - include threat detection events in a Whispir communications workflow, or automate the delivery of security system reports with event-based rules. **Business operations** - to connect PagerDuty incidents to an Amazon Redshift data warehouse, so you can analyze the remediation velocity and average operational load on engineering teams. **Application monitoring** - send load volume alerts from DataDog to EventBridge to trigger an AWS Lambda function that scales your EC2 instances to handle the expected load increase. **Directory registration** - send new user creation events from OneLogin to EventBridge, and route them to a Lambda function that makes technical resources available to newly hired engineers. **Customer data updates** - you can send an event to EventBridge when the status of a SugarCRM opportunity changes to “Closed Won,” and trigger a workflow that will provision billing records |
| Simple Notification Service | Pub/Sub , Mobile Push and SMS | [SNS](https://aws.amazon.com/sns/?c=2&pt=4) | SNS reliably delivers messages to all supported AWS endpoints, such as Amazon **SQS queues and AWS Lambda functions. In case the subscribed endpoint isn't available, Amazon SNS executes message delivery retry policies and can also move messages to dead-letter queues (DLQ).** **Message Filtering** - simplify your pub/sub messaging architecture by offloading the message filtering logic from your subscriber systems, and message routing logic from your publisher systems. CloudWatch gives visibility into your filtering activity, and CloudFormation enables you to deploy subscription filter policies in an automated and secure manner. **** |
| Simple Queue Service / SQS FIFO | managed message queues for microservices, distributed systems, and serverless applications
| [SQS](https://aws.amazon.com/sqs/?c=2&pt=5) | **Reliably deliver messages** - tansmit any volume of data, at any level of throughput, without losing messages or requiring other services to be available **sensitive data secure** - exchange sensitive data between applications using server-side encryption (SSE) to encrypt each message body **** |
| AppSync | Power your applications with the right data, from one or more data sources, at global scale | [AppSync](https://aws.amazon.com/appsync/?c=2&pt=6) | **Real Time Collaboration** - broadcasting data from the backend to all connected clients (one-to-many) or broadcasting data between clients themselves (many-to-many) **Chat Applications** - build a mobile and web application that supports multiple private chat rooms, offers access to conversation history, and enqueues outbound messages, even when the device is offline **Internet of Things** - build a real-time dashboard in a mobile or web application to visualize telemetry from a connected car **Data Layer** - AppSync as a single interface to access and combine data from multiple microservices in your application. **Polyglot Backend Data Access** - retrieve or modify data from multiple data sources (SQL databases in Amazon Aurora Serverless, NoSQL tables in Amazon DynamoDB, search data in Amazon Elasticsearch Service, REST endpoints in Amazon API Gateway, or serverless backends in AWS Lambda) with a single call **Offline** - Update data when the client reconnects. |


</details>

### 📦 Bigger Picture 
<details>
<summary>View Snapshot</summary>

#### Engineering
|  Name |  Summary | Details  | Use cases |  
|:-:    |:-:       |:-:       |:-:        |  
| | | []() | **** **** **** |
| | | []() | **** **** **** |


</details>

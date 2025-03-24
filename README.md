 [Core Components](#core-components)
 
## What is Systems Design – Learn System Design

Systems Design is the process of defining the architecture, components, modules, interfaces, and data for a system to satisfy specified requirements. It involves translating user requirements into a detailed blueprint that guides the implementation phase. The goal is to create a well-organized and efficient structure that meets the intended purpose while considering factors like scalability, maintainability, and performance.

![Alt text](https://media.geeksforgeeks.org/wp-content/uploads/20221117160614/systemdevelopmentinfographic1.png "Title")

## Core Components
Below are some of the major components of the System Design. discussed in brief. The detailed version of this will be discussed in different posts:

* **Load Balancers:**
    * Distribute incoming traffic across multiple servers to optimize performance and ensure reliability.
    * Prevents single server overload and enhances system availability.
* **Key-Value Stores:**
    * Storage systems that manage data as pairs of keys and values.
    * Often implemented using distributed hash tables for efficient data retrieval.
    * Examples: Redis, Memcached.
* **Blob Storage:**
    * A service for storing large amounts of unstructured data, such as media files.
    * Scalable and cost-effective for handling large binary objects.
    * Examples: Amazon S3, Azure Blob Storage.
* **Databases:**
    * Organized collections of data that facilitate easy access, management, and modification.
    * Distributed databases offer horizontal scaling and fault tolerance.
    * Examples: Cassandra, CockroachDB.
* **Rate Limiters:**
    * Control the maximum number of requests a service can handle in a given timeframe.
    * Prevent overload and ensure fair resource allocation.
    * Essential for protecting services from abuse.
* **Monitoring Systems:**
    * Tools that enable administrators to track and analyze infrastructure performance.
    * Monitor metrics like bandwidth, CPU usage, and latency.
    * Examples: Prometheus, Grafana.
* **Distributed Messaging Queues:**
    * Mediums that facilitate communication between producers and consumers.
    * Ensure reliable message delivery and decouple system components.
    * Examples: Kafka, RabbitMQ.
* **Distributed Unique ID Generators:**
    * Systems that generate unique identifiers for events or tasks in a distributed environment.
    * Essential for tracking and managing data across multiple nodes.
    * Examples: Snowflake, UUID generation services.
* **Distributed Search:**
    * Mechanisms that allow users to search across multiple data sources or websites for relevant information.
    * Enable efficient and scalable search capabilities.
    * Examples: Elasticsearch, Solr.
* **Distributed Logging Services:**
    * Systems that collect and trace logs across services to monitor and troubleshoot applications.
    * Provide centralized log management for distributed environments.
    * Examples: ELK Stack (Elasticsearch, Logstash, Kibana).
* **Distributed Task Schedulers:**
    * Tools that manage and allocate computational resources for executing tasks across a distributed system.
    * Enable parallel processing and efficient resource utilization.
    * Examples: Apache Airflow, Kubernetes Jobs.
  

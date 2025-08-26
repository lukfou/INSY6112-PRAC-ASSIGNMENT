# INSY6112-PRAC-ASSIGNMENT
ST10443474 - Luke Fourie

Question One:
The rapid growth of social media platforms requires powerful data storage and management solution system. With millions of users creating varied and dynamic content like text, images, videos, likes, and comments, the database system needs to be capable of handling large quantities of both structured and unstructured data efficiently. This report recommends whether a relational or NoSQL database must be used for the platform. The discussion includes a definition of the recommended database type, motivations for which selection chosen, examples of data stored, types of NoSQL databases, and an analysis of the three Vs of Big Data. 

 

Recommendation of Database Type

A NoSQL database should be used by the social media network. A NoSQL database (Not Only SQL) is a non-relational database system that allows schema-less or semi-structured data to be stored. It is ideal for managing large amounts of and varied data demands because of its high performance, distributed data storage, and horizontal scalability (MongoDB, 2025; Akamai, 2022). 

 

Motivations for Selecting NoSQL 

High Volume and Horizontal Scalability 

Social media creates large amounts of content in real time. NoSQL databases are designed to scale horizontally across many different servers, allowing high throughput and storage capability without the system being bottlenecked (MongoDB, 2025; Atlan, 2025). 

Flexible, Schema-Less Data Structures 

Text, photos, videos, GIFs, and likes are just some of the many formats in which user interactions take place.  Schema-less storage is supported by NoSQL databases, which removes the need for complex migrations and allows flexibility in response to changing the structure of data (Curate Partners, 2023; Akamai, 2022). 

Real-Time Analytics and Low Latency 

Users anticipate real-time interaction updates, such as likes and notifications.  NoSQL systems are perfect for real-time analytics since they are designed for fast reading and writing operations, especially in key-value and wide-column databases (Oracle, 2025; Knowi, 2025). 

 

Types of Data Stored in NoSQL Databases 

NoSQL is a database systems family rather than a single technology that was made to overcome the faults of conventional relational databases in managing workloads involving large quantities of varied, dynamic data.  There are four main NoSQL database types (document, key-value, wide-column, and graph) which can be used in collaboration for social media platforms to meet its various needs. 

  

Document databases such as MongoDB and Cosmos DB are highly suitable for storing user-generated content, including posts, comments, and profile information. These systems store information in JSON-like documents, which are flexible and allow fields to be added or modified without requiring schema changes. This adaptability makes them particularly well-suited for social media platforms, where new content types and metadata are frequently introduced (MongoDB, 2025). Document databases also provide powerful querying capabilities, enabling efficient retrieval of user-specific data or content feeds. 

  

Key–value stores, like Redis and Oracle NoSQL, are an essential part. They are optimized for speed and simplicity; they store data as unique keys paired with values. In the context of social media, they are especially effective for managing session data, caching timelines, or recording high-volume counters such as likes and shares on the platforms. Their low-latency operations make them ideal for handling real-time features such as notifications and updates (Akamai, 2022; Oracle, 2025). 

  

Apache Cassandra and other wide-column databases are critical for distributed performance and scalability.  These databases allow linear scalability and fault tolerance and are made for large datasets that are spread over many different servers.  Cassandra has been used by social media platforms such as Facebook to handle large amounts of interactions every day, especially for feeds and logs that require constant writing and reading.  It is ideal for platforms all over the world that can’t afford downtime due to its distributed architecture, which guarantees high availability without a single point of failure (Apache Cassandra, 2025; Knowi, 2025; Lenovo, 2025). 

  

Lastly, graph databases such as Neo4j are useful for modeling relationships in the social graph section of the platform.  Users are represented as nodes in graph databases, instead of relational or columnar storage, and their relationships (things such as friendships, followers, and recommendations) are represented as edges.  This framework makes it possible to execute sophisticated queries efficiently, such as finding mutual friends or producing recommendations for specific content.  Graph databases offer a natural and efficient method of maintaining relationships, which are the basis of social networking (Curate Partners, 2023). 

  

In practice, a mixed strategy is most commonly used, with each type of NoSQL database supporting a specific workload within the overall system.  Key-value systems can power caches and sessions, document stores can handle posts and content, wide-column databases can handle extensive analytics, and graph databases can simulate social relationships.  When all is combined, they offer the performance, scalability, and flexibility that is needed to meet the needs of a contemporary social media platform. 

 

 

Types of NoSQL Databases 

Document Databases 

Examples such as MongoDB and Cosmos DB. These databases store data as JSON-like files and allow the evolution of flexible schema. They are particularly useful for storing dynamic user-generated content like posts and profiles (MongoDB, 2025). 

Key–Value Stores 

Examples such as Redis and Oracle NoSQL. They keep information as key-value pairs and deliver very high-speed reads and writes, making them perfect for caching feeds, notifications, and user sessions (Akamai, 2022; Oracle, 2025). 

Wide-Column Stores 

Examples such as Apache Cassandra and HBase. They are optimized for large-scale workloads across clusters with high write throughput. These systems are commonly used for real-time analytics, feeds, and log data (Apache Cassandra, 2025; Lenovo, 2025; Knowi, 2025). 

Graph Databases 

Examples such as Neo4j. These databases capture relationships like friendships, followers, and content recommendations. They allow efficient relationship queries and are important for features such as social graph analysis and recommendation systems (Curate Partners, 2023). 

 

The Three Vs of Big Data 

Volume 

The platform creates large amounts of multimedia data that requires a distributed database solution. NoSQL databases handle this by horizontal scaling and sharding (Atlan, 2025). 

Velocity 

Social interactions happen in real time, needing rapid ingestion and processing. NoSQL systems support low-latency updates and fast response times, which is critical for a users experience (Oracle, 2025). 

Variety 

The platform handles structured (ie. profiles), semi-structured (ie. JSON posts), and unstructured (ie. videos, images) data. NoSQL databases support all these types of data without rigid schemas (Akamai, 2022; MongoDB, 2025). 

 

The social media platform should use a NoSQL database, as discussed in this report.  Its ability to manage large amounts of diverse data, facilitate real-time analytics, and expand horizontally across different servers is the basis of these recommendations.  Together, the various NoSQL database types, such as document, key-value, wide-column, and graph databases, can meet the platform's different data requirements while adhering to the three Vs of Big Data (variety, velocity, and volume). 

 

Question 2: 

<img width="782" height="524" alt="Screenshot 2025-08-25 220007" src="https://github.com/user-attachments/assets/e12545f6-d8a8-4205-86eb-38516e2df341" />

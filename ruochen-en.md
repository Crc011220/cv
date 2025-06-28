# Ruochen Chen

> <span class="icon">&#xe60f;</span> `13738337771`&emsp;
> <span class="icon">&#xe7ca;</span> `ruocchen1220@gmail.com`&emsp;
> <span class="icon">&#xe600;</span> https://github.com/Crc011220&emsp;
> <span class="icon">&#xe673;</span> https://blog.rcchen.dpdns.org


<!-- <img class="avatar" src=""> -->

## &#xe80c; Education

<div class="entry-title">
    <h3>University of Melbourne - Master of Information Technology</h3> 
    <p>2024.02 - 2025.12</p>
</div>
Specializing in Computing

- Relative Courses: Programming and Software Development, Internet Technology, Algorithms and Complexity, Database Systems and Information Modelling, Distributed Systems, Software Process and Management, Machine Learning, Cluster and Cloud Computing, Declarative Programming, Information Visualization

<div class="entry-title">
    <h3>University of Melbourne - Bachelor of Arts</h3> 
    <p>2020.08 - 2023.12</p>
</div>
Major in Psychology, Minor in Economics

## &#xecfa; Technical Skills
- Proficient in JavaSE core syntax, with deep understanding of Collections Framework, Multi-threading (Thread Safety, Thread Pool), JVM (Memory Structure, Class Loading Mechanism, Garbage Collection Algorithms).
- Expert in Spring ecosystem (Spring Boot, Spring MVC, MyBatis-Plus), with thorough understanding of IOC, AOP design principles.
- Experienced in microservices architecture design and development, proficient with Spring Cloud ecosystem (including Nacos, OpenFeign, Gateway components).
- Strong knowledge of MySQL database development, including index optimization, transaction isolation levels, and locking mechanisms.
- Proficient in Redis core data types and underlying data structures, with expertise in cache update strategies and solutions for cache penetration/breakdown/avalanche.
- Experienced with message queues (RocketMQ/Kafka), including dead letter queue design, message reliability assurance, and cluster deployment.
- Strong understanding of TCP/IP network model and protocols (HTTP, TCP/UDP, DNS).
- Proficient in Linux systems and common commands, containerization technologies (Docker, Kubernetes), and Serverless architecture.
- Hands-on experience with cloud platforms (AWS, Alibaba Cloud, OpenStack), holding AWS Certified Cloud Practitioner certification.
- Knowledge of common design patterns (Singleton, Factory, Strategy, Observer, Decorator) and their applications.
- Basic understanding of LangChain and Spring AI applications, exploring AI integration development.
- Frontend development skills with Next.js, Vue, TailWind CSS frameworks, capable of full-stack development collaboration.

## &#xe618; Professional Experience

<div alt="entry-title">
    <h3>Full Stack Development Intern - JD</h3> 
    <p>May 2025 - July 2025</p>
</div>

Scheduled Task Management System (Spring Boot + Spring Security + MyBatis Plus + Redis + React)
- Led the development of an enterprise-level distributed scheduled task management platform, building the core scheduling engine with Spring Boot and XXL-JOB, supporting Cron expression configuration and task failover.
- Designed a multi-layer fault-tolerant architecture, achieving zero single point of failure through application clustering, database master-slave, and distributed task scheduling, ensuring 99.9% system availability with automatic failover and uninterrupted service.
- Designed and implemented a comprehensive RBAC permission management system, integrating Spring Security and JWT for fine-grained access control, ensuring system security and compliance of user operations.
- Developed a React + TypeScript front-end monitoring dashboard, integrating real-time task status display, execution log query, and performance statistics charts, enhancing operational monitoring efficiency and user experience.
- Established an automated quality assurance process, integrating Git Hooks pre-commit validation and GitHub Actions for continuous integration, combined with JUnit 5 unit testing framework to ensure code quality and system stability.


<div alt="entry-title">
    <h3>Full Stack Development Intern - China Merchants Bank</h3> 
    <p>2024.11 - 2025.03</p>
</div>


Internal Lean Management Platform Construction (Spring Boot + Vue.js + Redis + Kafka + ECS)
- Led the development of a versatile Excel data processing framework, supporting parsing and reading/writing of headers with any structure, adaptable to various business data formats. Achieved stable performance for importing and exporting data at a scale of 100,000 entries through asynchronous batch processing, data partitioning, and cache optimization, providing foundational support for multiple business modules.
- Designed and implemented an automated generation and validation process for software development deliverables (e.g., test reports, design documents). Built an intelligent review bot based on Prompt Engineering and domain knowledge base, which automatically suggests document modifications, reducing manual review by approximately 75%, effectively enhancing the standardization and delivery efficiency of development documentation.

Business Marketing and Promotion Management System Development (Spring Boot + Nacos + Selenium + Scrapy)
- Led the construction of a unified notification microservice system, encapsulating components for email, application messages, and SMS sending. Integrated Nacos for configuration management and service registration, supporting flexible invocation and dynamic expansion, enhancing the uniformity and maintainability of inter-system message notifications.
- Participated in the development of the opportunity mining module, implementing automated data collection from multiple sites based on Selenium and Scrapy, supporting rule configuration and content filtering, improving the coverage and quality of marketing data.

Cloud-Native Management Platform and CI/CD Pipeline Practice
- Led the deployment and integration of multiple Spring Boot interface projects, practicing cloud-native service governance, ensuring the stability and continuous delivery capability of the system launch process.

<div alt="entry-title">
    <h3>Junior IT All Rounder - AAkonsult PTY LTD</h3> 
    <p>July 2024 - November 2024</p>
</div>

Payment Form Portal Development (Salesforce Experience Cloud + Apex + Python + React + Figma)
- Developed a payment form portal based on Salesforce Experience Cloud, optimizing the interactive interface and functional modules to enhance user operation fluency.
- Learned and utilized Apex to develop backend business logic (e.g., data query interfaces, status update functions), improving code quality through debugging and code review, familiarizing with Salesforce platform workflows.
- Developed an automated calculation tool based on React, achieving real-time validation of user input and one-click export of results, enhancing data processing efficiency.
- Utilized Python to build batch analysis scripts for user input, optimizing the knowledge base data cleaning and classification process, improving analysis efficiency.
- Designed high-fidelity prototypes using Figma, combined with Statamic to implement multi-platform dynamic content management, enhancing visual appeal and increasing average user dwell time.


## &#xe635; Projects

<div class="entry-title">
    <h3>Cryptocurrency Trading Platform</h3>
    <a href="https://github.com/Crc011220/coin-exchange">GitHub</a>
</div>

Tech Stack: Spring Boot, Spring Cloud, Spring Security, MyBatis-Plus, Redis, JWT, AWS, Docker, RocketMQ, Disruptor, Tio
- Designed microservice architecture using Spring Cloud, implementing service registration and configuration center with Nacos, service communication via OpenFeign, and server-side load balancing with LoadBalancer.
- Implemented OAuth2.0 + JWT security authentication system, ensuring RESTful API communication security with cross-service authentication via OpenFeign.
- Utilized Redis for caching access tokens and verification codes, optimizing system performance under high concurrency.
- Containerized middleware deployment to AWS EC2 using Docker, integrated S3 for static resource storage and SNS for SMS notifications.
- Integrated GeeTest captcha and Alibaba Cloud identity verification to enhance user registration security.
- Designed distributed global ID generation system based on Snowflake algorithm, implementing distributed locks with JetCache.
- Implemented real-time message distribution using RocketMQ in matching engine, utilizing Disruptor's RingBuffer for asynchronous order processing.
- Integrated WebSocket (Tio + RocketMQ) for real-time market data push.
- Implemented efficient K-line data storage and management using Spring Boot scheduled tasks and Redis List.

<div class="entry-title">
    <h3>Lightweight RPC Framework</h3> 
    <a href="https://github.com/Crc011220/RPC">GitHub</a>
</div>
Tech Stack: Java, Netty, Zookeeper, Redis

- Replaced traditional blocking I/O with Netty's NIO features, significantly improving network communication efficiency.
- Implemented transparent service invocation mechanism using dynamic proxy technology, simplifying client-server interaction.
- Designed custom RPC protocol supporting multiple serialization schemes (Java native serialization, JSON, etc.).
- Integrated Zookeeper for service registration and discovery, incorporating Redis caching to reduce Zookeeper load and ensure high availability.
- Implemented various load balancing algorithms (random, round-robin, etc.) to optimize service provider traffic distribution.


<div class="entry-title">
    <h3>Cloud-Based Data Analysis</h3> 
</div>
Tech Stack: Python, NeCTAR Research Cloud, Kubernetes, Docker, Fission, Elasticsearch

- Deployed platform on NeCTAR Research Cloud instances, managing Docker containers with Kubernetes for high availability and scalability.
- Built distributed search engine system based on Elasticsearch, enabling efficient indexing and fast retrieval of large-scale data.
- Implemented scheduled data collection from multiple social media platforms using Kubernetes' serverless computing framework Fission (Cron Jobs), with real-time writing to Elasticsearch cluster.
- Automated container replica scaling in Kubernetes based on real-time Elasticsearch cluster load, achieving dynamic resource scheduling and elastic scaling.
- Integrated natural language processing tools (NLTK, VADER, TextBlob) in Python environment for sentiment analysis, keyword extraction, and text classification; built interactive analysis interface with Jupyter Notebook supporting dynamic visualization.
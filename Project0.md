#1010Data

	Intro: It’s a cloud platform that provide data analysts service for big data discovery and data sharing.
	Pros: Eliminate the need for hardware/software design or programming while provide high scalability, efficiency and speed.
	Cons: All customs is accessing the same data, it will have delay and conflicts.
	Reference: https://www.1010data.com/

#Accumulo 
	Intro: Accumulo is a project built on top of Hadoop, ZooKeeper and Thrift. It provides key-value store and retrieval.
	Pros: Cell level security allows data with different access control stored in the same table.
	Cons: Less popular and not widely used.
	Reference: https://accumulo.apache.org/

#Actian Ingres
	Intro: It’s a relational database developed for enterprise.
	Pros: Hardware scalability, replication and distributed option
	Cons: Recovery server was not stable
	Reference: http://community.actian.com/forum/database-migration/1002-ms-sqlserver-vs-ingres.html

#Actian PSQL
	Intro: Database for packaged business application.
	Pros: VM live migration capabilities, support UNICODE
	Cons: ?
	Reference: http://www.pervasive.com/database/Home/Products/PSQLv12.aspx

#Actian Vector
	Intro: Analytics database with high performance and price/performance while requires less hardware and virtually no database tuning
	Pros: Vector processing, Column-based storage, On-chip cache computing. In sum, get fast by parallelism.
	Cons: The speed can only achieved when there’s  large data processed by single instruction.
	Reference:http://www.ticout.com/descargas/Actian-Vector-Datasheet.pdf

#Actian Versant
	Intro: Object database solution
	Pros: Cover the gap between relational data base and object oriented language.
	Cons: Having multiple instance at the same time may impact query performance
	Reference: http://developer.versant.com/developer/resources/objectdatabase/documentation/VODAdministration.pdf

#Adabas
	Intro: Software AG’s primary database management system
	Pros: Performance and hierarchy model
	Cons: Poor communication to some languages
	Reference:http://en.wikipedia.org/wiki/ADABAS
		      http://ibmmainframes.com/about15310.html

#Aerospike
	Intro: Open source distributed Key-Value NoSQL database.
	Pros: Solves the key-value problem for application developers while achieve scalability
	Cons: Not useful when the workload is read only.
	Reference:http://www.infoq.com/articles/aerospike-qa

#Allegrograph
	Intro: AllegroGraph is a database and application framework for building Semantic Web applications.
	Pros: Extremely fast for connected data and easy to query
	Cons: Searching node on different machine will slow the process
	Reference: http://data-magnum.com/lesson-8-graph-databases-including-object-dbs/

#Altibase HDB
	Intro: Hybrid DBMS with hybrid architecture that combines an in-memory database with a conventional disk-resident database.
	Pros: Be able to achieve consistency and scalability at the same time. Include checkpoints, high-availability(HA), fault tolerance and load balancing
	Cons: Speed is not fast compared to XDB
	Reference: http://altibase.com/in-memory-database-comparisons/altibase-memory-database-vs-apache-cassandra-nosql-open-source-database/#toggle-id-2

#Altibase XDB
	Intro: Traditional relational database that has fast data processing speeds in main-memory
	Pros: High-availability, replication, and scalability
	Cons: Expensive
	Reference: http://en.wikipedia.org/wiki/Altibase#Altibase_XDB

#Altiscale
	Intro: Altiscale offers the first cloud service that is purpose-built to run Apache Hadoop
	Pros: Provide hardware, software, troubleshooting for Hadoop service
	Reference: https://issues.apache.org/jira/browse/HDFS-6469

#Apache Drill:
	Intro: Open source software framework that supports data-intensive distributed applications for interactive analysis of large-scale datasets.
	Pros: Nested data and no schema
	Ref:http://www.slideshare.net/julianhyde/drill-sql-optiq

#Apache Hive
	Intro: Data warehouse infrastructure built on top of Hadoop for providing data summarization, query and analysis.
	Pros: Matured and good support.
	Cons: Brings in all MapReduce advantage like expensive shuffle phase and lot slower
	Ref: https://bigdatanerd.wordpress.com/2013/11/19/war-on-sql-over-hadoop/

#Apache S4
	Intro: Distributed stream processing engine inspired by the MapReduce model
	Pros: General-purpose,near real-time, distributed, decentralized, scalable, event-driven, modular platform that allows programmers to easily implement applications for processing continuous unbounded streams of data
	Cons: Lacks dynamic load balancing and robust live PE migration
	Reference: http://cs.brown.edu/~debrabant/cis570-website/papers/s4.pdf

#Apache Storm
	Intro:Storm is a distributed real-time computation system for processing large volumes of high-velocity data
	Pros: Fast, scalable, fault-tolerant, reliable, easy to operate
	Cons: It has not any capabilities to find out event patterns.
	Reference: http://www.quora.com/Apache-Storm

#Apache Tajo
	Intro: Apache Tajo is a robust big data relational and distributed data warehouse system for Apache Hadoop
	Pros: Incorporates the advantages of MapReduce and Parallel databases
	Reference:http://www.quora.com/search?q=apache+tajo+disadvantage

#ArangoDB
	Intro: Multi-purpose No-SQL Database
	Pros: Extendable from JS, high performance&space efficiency, multi-model database
	Cons: Document query may have large overhead.
	Reference: http://www.slideshare.net/arangodb/arangodb-a-different-approach-to-nosql
		       https://groups.google.com/forum/#!topic/arangodb/xzE3UgUfqDQ

#AWS DynamoDB
	Intro: Fast and flexible NoSQL database service
	Pros: Single-digit millisecond latency, support both document and key-value data models.
	Cons: Limited row size and querying size. Limited to AWS. Don’t support complex query and secondary indexes.
	Reference: http://www.slideshare.net/saniyakhalsa/dynamo-db-pros-and-cons
		       http://aws.amazon.com/dynamodb/

#AWS ElasticCache
	Intro: Web service that allow to use an in-memory cache in the cloud.
	Pros: Easy to use, single DNS per cluster
	Cons: Suffer from fault event—not reliable
	Reference: http://www.quora.com/What-are-the-advantages-and-disadvantages-of-using-AWS-Elasticache-over-self-hosted-Memcached

#AWS EMR
	Intro: Web service that uses hadoop
	Pros: Simple and easy to use. Easy to solve large questions
	Cons: Costly when run regularly. 
	Reference: http://www.quora.com/What-are-the-advantages-disadvantages-running-Clouderas-distribution-for-Hadoop-on-EC2-instances-rather-than-using-Amazons-Elastic-Map-Reduce-Service

#AWS Kinesis
	Intro: Cloud based service for real-time processing for large distributed data streams.
	Pros: Make data import process manageable
	Cons: One still need to manually import data to AWS
	Reference: http://www.quora.com/What-can-you-do-with-Amazon-Kinesis

#AWS RDS
	Intro: Cloud based relational database
	Pros: Automatic backup and maintain
	Cons: Not applicable for highly secret data 
	Reference: http://www.laurencegellert.com/2013/05/pros-and-cons-of-rds-vs-ec2-for-mysql-with-aws/

#AWS Redshift
	Intro: Data warehouse in cloud
	Pros: AWS and SQL, therefore easy to learn. Fast, cheap and scalable
	Cons: Not fast enough, does’t enforce uniqueness.
	Reference: http://www.quora.com/What-are-the-pros-and-cons-of-using-Amazon-Redshift

#AWS SimpleDB
	Intro: Non-relational data store 
	Pros: Developers just store and query the data.
	Cons: Consistency not guaranteed. Limited attribute size
	Reference: http://highscalability.com/current-pros-and-cons-list-simpledb

#Azure DocumentDB
	Intro: NoSQL document database
	Pros: Schema free JSON data
	Cons: Schema is actually important.
	Reference: http://ayende.com/blog/168034/azure-documentdb

#Azure Search
	Intro: Cloud-based service that allows users to build search applications using REST api
	Pros: Doesn’t require search knowledge
	Cons: Limited to Windows family
	Reference: http://www.cloudpro.co.uk/paas/cloud-development/223/azure-versus-amazon-weighing-options

#Azure SQL database
	Intro: Relational, cloud-based database
	Pros: Scalable, no maintenance cost, backup
	Cons: Limited database size(500 GB)
	Reference: http://www.piraeusconsulting.com/blog/microsoft/sql-server/azure-sql-database-vs-sql-server-in-azure-vm/

#BerkeleyDB
	Intro: Software library for key/value database
	Pros: Fast with cache and portable across platforms
	Cons: Performance is worse in little endian
	Reference: https://people.ok.ubc.ca/rlawrenc/teaching/416/Notes/416_13_BerkeleyDB_by6.pdf
	
#BitYota
	Intro: Data-warehouse as a service
	Pros: Reduce effort to maintain, cost of hardware and software. Auto detect different format.
	Cons: 
	Reference: http://cloudcomputingeurope.sys-con.com/node/2466082

#Cassandra
	Intro: Open source distributed database management system
	Pros: Simple setup, maintenance and code. Fast Reads&Writes
	Cons: Not support secondary indexes, relational data.
	Reference: http://www.slideshare.net/EdurekaIN/no-sql-databases-35591065

#ClearDB
	Intro: Database-as-a-service for MySQL applications
	Pros: Significant time&cost saving
	Cons: Lost control, learning curve
	Reference: http://www.cleardb.com/blog/entry?id=pro-series/segment-101/why-use-a-database-as-a-service-instead-of-do-it-yourself-mysql-in-the-cloud

#Cloudant
	Intro: Distributed Database-as-a-service 
	Pros: Cheap, support JSON and REST API
	Cons: Not applicable for moving existing architecture&data
	Reference: http://support.huawei.com/ecommunity/bbs/10167573.html

#Cloudera
	Intro: Hadoop based enterprise data-hub
	Pros: Support hadoop
	Cons: Open source therefore not pure
	Reference: http://www.dbms2.com/2011/07/10/cloudera-and-hortonworks/

#Hortonworks
	Intro: Hadoop based service
	Pros: Runs on Windows and Linux
	Cons: Not widely used as Cloudera
	Reference: http://www.quora.com/What-distribution-should-I-choose-Cloudera-Hortonworks-or-MapR

#Clustrix
	Intro: Scale-out SQL database
	Pros: Fast and fault tolerant
	Cons: Hard to transfer data, no standard way to access
	Reference: http://www.odbms.org/blog/2012/10/two-cons-against-nosql-part-i/

#DeepDB
	Intro: General purpose database for Big Data
	Pros: Real time accelerator and storage optimizer
	Cons: Limited to MySQL
	Reference: http://bigdata.sys-con.com/node/3080848

#ElasticSearch
	Intro: End to end search and analysis platform
	Pros: Schemaless, nested docs and analyzer per doc& query
	Cons: Only JSON, less support out of box
	Reference: http://www.ymc.ch/en/why-we-chose-solr-4-0-instead-of-elasticsearch

#HBase
	Intro: Open source, non relational, distributed database
	Pros: Scalable, consistency, built on top of hadoop
	Cons: Not optimized 
	Reference: http://www.slideshare.net/EdurekaIN/no-sql-databases-35591065

#MongoDB
	Intro: Cross platform document database
	Pros: Schema-free, full index support, redundancy
	Cons: Not applicable to traditional database or highly transactional applications.
	Reference: http://www.slideshare.net/EdurekaIN/no-sql-databases-35591065

#MySQL
	Intro: Open Source Relational Database
	Pros: Widely used
	Cons: Open source and Oracle managed instead of community
	Reference: http://www.smartfile.com/blog/the-pros-and-cons-of-mysql/


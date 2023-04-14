# Reading 3.9: Choose the Right AWS Database Service

## **AWS Database Services**

AWS has a variety of different database options for different use cases. Use the table below to get a quick look at the AWS database portfolio.

| Database Type | Use Cases | AWS Service |
| --- | --- | --- |
| Relational | Traditional applications, ERP, CRM, e-commerce | Amazon RDS, Amazon Aurora, Amazon Redshift |
| Key-value | High-traffic web apps, e-commerce systems, gaming applications | Amazon DynamoDB |
| In-memory | Caching, session management, gaming leaderboards, geospatial applications | Amazon ElastiCache for Memcached, Amazon ElastiCache for Redis |
| Document | Content management, catalogs, user profiles | Amazon DocumentDB (with MongoDB compatibility) |
| Wide column | High-scale industrial apps for equipment maintenance, fleet management, and route optimization | Amazon Keyspaces (for Apache Cassandra) |
| Graph | Fraud detection, social networking, and recommendation engines | Amazon Neptune |
| Time series | IoT applications, DevOps, industrial telemetry | Amazon Timestream |
| Ledger | Systems of record, supply chain, registrations, banking transactions | Amazon QLDB |

## **Breaking Up Applications and Databases**

As the industry changes, applications and databases change too. Today, with larger applications, you no longer see just one database supporting it. Instead, these applications are being broken into smaller services, each with its own purpose-built database supporting it.

This shift removes the idea of a one-size-fits-all database and replaces it with a complimentary database strategy. You can give each database the appropriate functionality, performance, and scale that the workload requires.

**Resources**:

- *[External Site:* AWS: Databases on AWS](https://aws.amazon.com/products/databases/)
- *[External Site:* AWS: AWS Database Blog](https://aws.amazon.com/blogs/database/?nc=sn&loc=4)
- *[External Site:* AWS: Database Freedom](https://aws.amazon.com/products/databases/freedom/?nc=sn&loc=5)

[<< Prev](Reading%203%207%20Introduction%20to%20Amazon%20DynamoDB.md)
|
[Netx >>]()

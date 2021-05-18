# Databases

## Relational
Data is organized in one or more tables (formed by columns or attributes and rows or records), where a unique key. In
general, a table/relation represents one entity type. Rows represent instances of those entities and columns represent
the values attributed to that instance. Relationships between tables or entities are done using foreign keys (unique
keys of the linked entity).

Use when:
- Situations where data integrity is absolutely paramount (i.e.: financial applications, defense and security, and
private health information).
- Highly structured data.
- Automation of internal processes.

### MS Server
_License_: Propietary.

_Operative Systems_: Linux, Windows.

_Implementation_: C/C++.

- [MS-SQL Server official webpage](https://www.microsoft.com/en-us/windows-server/).
- [MS-SQL Server GitHub repository](https://github.com/microsoft?q=mssql&type=&language=&sort=).

### MySQL
_License_: GLPv2 and propietary.

_Operating Systems_: Linux, Windows, macOS, Solaris, FreeBSD, _etc_.

_Implementation_: C/C++.

- [MySQL official webpage](https://www.mysql.com).
- [MySQL GitHub repository](https://github.com/mysql).

### Oracle SQL
_License_: Propietary.

_Operating Systems_: Anything that supports JVM.

_Implementation_: Java.

- [Oracle SQL official webpage](https://www.oracle.com/database/technologies/appdev/sqldeveloper-landing.html).

### PostgreSQL
_Liscense_: PostgreSQL License (free and open-source, permissive).

_Operating Systems_: macOS, Windows, Linux, FreeBSD, OpenBSD.

_Implementation_: C.

- [PostgreSQL official webpage](https://www.postgresql.org/).
- [Postgre GitHub repository](https://github.com/postgres).

## Non-Relationtal
A type of database that describes a database with flexible storage and retrieval. They also deal with high volumes of
unstructured data at a lower cost.

### Document Store
Non-relationtal database that stores data in JSON, BSON or XML documents. They feature a flexible schema. Unlike SQL
databases, where users must declare a table's schema, before inserting data, document stores don't enforce document
structure.

Use when:
- Unstructured or semistructured data.
- Content management.
- In-depth data analysis.
- Rapid prototyping.

#### Couchbase
_License_: Apache License 2.0.

_Operating Systems_: Linux, Windows and macOS.

_Implementation_: C++, Erlang, C, Go.

- [Couchbase official webpage](https://www.couchbase.com/).
- [Couchbase GitHub repository](https://github.com/couchbase).

#### MongoDB
_License_: Server Side Public License.

_Operating Systems_: Linux, Windows, macOS, Solaris, FreeBSD.

_Implementation_: C++, JavaScript, Python.

- [MongoDB official webpage](https://www.mongodb.com/).
- [MongoDB GitHub repository](https://github.com/mongodb).
- [MongoDB University](https://university.mongodb.com/) - Free and guided  from MongoDB developers and professors.
- [Studio 3T Webpage](https://studio3t.com/) - It is a tool that allows writing in SQL and transforming them into
  MongoDB syntax. Don't worry, it's an [official partner](https://www.mongodb.com/partners/studio-3t). Can be a good
  starting point to familiarize with MongoDB syntax.
  
### Key-Value Store
Non-relational database where each value is associated with a specific key. It's  known as associative array. The "key"
is a unique identifier associated  with the value. Keys can be anything allowed by the DBMS.

Use when:
- Recommendations.
- User profile settings.
- Unstructured data such as product reviews or blog comments.
- Session management at scale.
- Data that will be accessed frequently but not often updated.

#### Memcached
_License_: Revised BSD license.

_Operating Systems_: Unix-based, Windows.

_Implementation_: C.

- [Memcached official webpage](https://www.memcached.org/).
- [Memcached GitHub repository](https://github.com/memcached).

#### Redis
_License_: BSD 3-clause.

_Operating Systems_: Unix-based.

_Implementation_: C.

- [Redis official webpage](https://redis.io/).
- [Redis GitHub repository](https://github.com/redis).

### Wide-Column Store
These are also called column stores or extensible record stores. They are  column-oriented non-relational databases. 
They're sometimes seen as a of key-value store but have attributes of traditional relational databases well.

Use when:
- Big data analytics where speed is important.
- Data warehousing on big data.
- Large scale projects (this database style is not a good tool for average applications).

#### Cassandra
_License_: Apache License 2.0.

_Operating Systems_: Anything that supports JVM.

_Implementation_: Java.

- [Cassandra official webpage](https://cassandra.apache.org/).
- [Cassandra GitHub repository](https://github.com/apache?q=cassandra&type=&language=&sort=).

#### HBase
_License_: Apache License 2.0.

_Operating Systems_: Anything that supports JVM.

_Implementation_: Java.

- [HBase official webpage](https://hbase.apache.org/).
- [HBase GitHub repository](https://github.com/apache?q=hbase&type=&language=&sort=).

### Search Engine
Non-relational document-based data storage and retrieval solution specially and optimized for the storage and rapid
retrieval of data.

Use when:
- Improving user experience with faster search results.
- Logging.

#### Elasticseach
_License_: Elastic License (propietary, source available) and Server Side Public License.

_Operating Systems_: Anything that support JVM.

_Implementation_: Java.

- [Elasticsearch official webpage](https://www.elastic.co/).
- [Elasticsearch GitHub repository](https://github.com/elastic/elasticsearch).

## Tools
### Backup Ninja
- [Backup Ninja Webpage](https://backup.ninja/technologies) - Tool to perform and 
  program backups for most OpenSource databases.

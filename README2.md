# IBM watsonx.data

IBM watsonx.data is a new open architecture lakehouse that combines the elements of the data warehouse and data lakes. The best-in-class features and optimizations available on the watsonx.data make it an optimal choice for next generation data analytics and automation. It is released in three versions:

1. Software
2. Developer
3. Cloud

# Latest version
IBM watsonx.data Version 1.1.3 is the latest version of IBM watsonx.data
This new version of watsonx.data was released in March 2024.

## Data lake House Overview - Challenges and Opportunities

A data lakehouse is a data platform, which merges the best aspects of data warehouses and data lakes into one data management solution. 

### Modern Lakehouse Solution Components

#### Engines

Engines enables querying, analytics and transformations for the lake house. The expectation is to enable the use of the right engine for the right workloads & use cases.

#### Metadara repository

A repository maintains schema and table metadata so that all engines and users can consistently locate and query against their data in a structured manner. Metadata is also stored with  open table formats; it serves  to define the file formats for  any tool that can read or write  open data formats.

#### Data storage

The data storage is where the data is physically stored.  Customers would expect to use their own storage such as S3 or HDFS and locate them wherever they need. With compute engines separated from storage, concurrent accesses by multiple engines must be enabled in the Lakehouse

#### Data Governance

A lakehouse needs to be able to enforce Data policies for access, privacy and safe harbor or sovereignty regulations  

#### Form factors : Cloud & on-premise  Service

Lakehouses need to be deployable or burstable  anywhere and even span clouds in a hybrid fashion.  Applications and end users would need to access lake houses engines from anywhere

## IBM watsonx.data Overview

1. IBM watsonx.data is an open, hybrid, and governed data store built on an open data lakehouse architecture. 

2. IBM watsonx.data is a core component of watsonx, IBM’s enterprise-ready AI and data platform designed to multiply the impact of AI across an enterprise’s business.  Other core components of watsonx are watsonx.ai and watsonx.governance
The watsonx platform comprises three powerful components: the watsonx.ai studio for new foundation models, generative AI and machine learning; the IBM watsonx.data fit-for-purpose data store that provides the flexibility of a data lake with the performance of a data warehouse; plus the watsonx.governance toolkit, to enable AI workflows that are built with responsibility, transparency, and explainability. 

3. The IBM watsonx.data component makes it possible for enterprises to scale analytics and AI with a data store built on an open lake house architecture, supported by querying, governance, and open data and table formats, to access and share data. 

4. With IBM watsonx.data, enterprises can connect to data in minutes, quickly get trusted insights, and reduce their data warehouse costs.

### IBM watsonx.data components and other details

#### Query Engines

Multiple Multiple engines such as Presto, Spark that provide fast, reliable, and efficient processing of big data at scale are supported. Prestissimo is a high performing engine that can supported certain types of workloads.  watsonx.data also supports cost-efficient compute and storage and fit-for-purpose analytics engines like Db2, Netezza that dynamically scale up and down.

#### Vector Databases

IBM watsonx.data has recently launched an integrated vector database, based on the open source Milvus, in the data lakehouse. Now, IBM watsonx customers can unify, curate and prepare vectorized embeddings for their generative artificial intelligence (gen AI) applications at scale across their trusted, governed data. The vector DB initially supported is based on open source vector DB Milvus. This supports upto 100 million vectors of 384 dimensions.

#### Governance and Metadata

Built-in governance is available in watsonx.data which can leverage existing IBM solutions like watsonx.governance and IBM Watson Knowledge Catalog

#### Open Data formats

Vendor agnostic open formats for analytic data sets, allowing different engines to access and share the same data, at the same time

Table formats such as Apache Iceberg which is a high-performance format for huge analytic tables is supported

Hive metastore supports allows customers to sync external deta sources with similar metastore

#### Cost-effective, simple object storage

Store large volumes of data in low-cost object storage and share it through an open table format built for high-performance analytics

#### Hybrid cloud deployments

Seamlessly deploy across any cloud or on-premises environment in minutes with workload portability through Red Hat® OpenShift®. Accelerate on-premises deployment and querying through integration with IBM® Storage Fusion HCI.
IBM watsonx.data available in SAAS (IBM Cloud, AWS) , Software ( with cloud pak for data , CPD) and developer edition ( as desktop install for developers to try out).

#### Easy-to-use integrated console

watsonx.data console allows you to connect to your existing analytics data across hybrid cloud and deploy query engines in minutes and explore and transform data with common SQL

## IBM watsonx.data developer version

IBM® watsonx.data developer version is an entry-level version for the developer and partner community. The developer version offers a set of containers on a suitable host machine at the same release level as the Enterprise version, with restricted features.
Installation instructions are available at https://www.ibm.com/docs/en/watsonxdata/1.1.x?topic=edition-installing-watsonxdata-developer-version

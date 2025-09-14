# HDFS and Apache Spark

Distributed storage and processing frameworks for big data analytics.

**Hadoop Distributed File System (HDFS)**:
- **Distributed Storage**: Files split into blocks across multiple machines
- **Fault Tolerance**: Automatic replication (typically 3x) for data durability
- **Scalability**: Can handle petabytes of data across thousands of nodes
- **Architecture**: NameNode (metadata) and DataNodes (actual data storage)

**Key HDFS Concepts**:
- **Blocks**: Default 128MB chunks for efficient storage and processing
- **Replication Factor**: Number of copies of each block
- **Rack Awareness**: Place replicas on different racks for fault tolerance
- **Data Locality**: Process data where it's stored to minimize network transfer

**Apache Spark**:
- **In-Memory Processing**: Keeps data in memory for faster computations
- **Unified Engine**: Supports batch, streaming, SQL, ML, and graph processing
- **Resilient Distributed Datasets (RDDs)**: Immutable distributed collections
- **Directed Acyclic Graph (DAG)**: Optimized execution plan

**Spark Ecosystem**:
- **Spark Core**: Basic functionality and RDDs
- **Spark SQL**: Structured data processing
- **MLlib**: Machine learning library
- **GraphX**: Graph processing
- **Structured Streaming**: Real-time data processing

**Advantages over Hadoop MapReduce**:
- 10-100x faster for iterative algorithms
- Interactive queries and ad-hoc analysis
- Rich APIs in multiple languages
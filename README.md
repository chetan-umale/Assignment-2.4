Q1-1. Explain hadoop in layman's term.
answer:
1.With the explosion of data, existing technologies became incapable of handling such large amount of data.
2.The most potent challenges were lack of storage and processing power.
3.Hadoop is a framework developed to meet these challenges.
4.Hadoop as such is not a programming language or a piece of hardware.But it is a collection of various components which work in collaboration to effectively handle Big Data.
5.The 2 basic building blocks of hadoop are- HDFS (Hadoop distributed File System) and MapReduce.
6.HDFS handles the storage of data while MapReduce handles the processing of data.
7.These programs are developed to run on commodity hardware which provides an alternative of scaling out whenever there is lack of storage or processing power.
8.Hadoop runs on a cluster of computers and not a single system.Companies like Yahoo,IBM etc. have clusters of more than 10000 computers running continuously to analyze large volumes of Data.
9.The Hadoop cluster work on master-slave architecture.


Q2-Explain the components of Hadoop framework.

answer:

The major components of Hadoop framework are 

1.Hadoop common:
Apache Foundation has pre-defined set of utilities and libraries that can be used by other modules within the Hadoop ecosystem. For example, if HBase and Hive want to access HDFS they need to make of Java archives (JAR files) that are stored in Hadoop Common.

2.HDFS:
HDFS is a distributed file system which is capable of storing large volumes of data on commodity hardware.It also uses blocks to store files but differs from traditional file systems by storing blocks contoguous memory locations thereby improving access time.
HDFS is further divided into 2 sub-components:
2.1 Name node:
The name node is the master node and is responsible for file system namespace and controls access to files by clients.
2.2 Data node:
The data nodes handles read-write requests from clients and sactually stores the blocks.They are responsible for creation,deletion and replication of data blocks.

3.MapReduce:
MapReduce is the  data processing paradigm used by hadoop.It is a batch processing programming model.
2.1 Job Tracker:
It assigns the new MapReduce tasks to task trackers and also reassigns the tasks whose execution failed.
2.2 Task Trackers:
Task tracker actually execute the MapReduce tasks  and sends it status back to job tracker. 

4.YARN:
YARN forms an integral part of Hadoop 2.0.YARN is great enabler for dynamic resource utilization on Hadoop framework as users can run various Hadoop applications without having to bother about increasing workloads.

5.PIG:
Apache Pig is a convenient tools developed by Yahoo for analysing huge data sets efficiently and easily. It provides a high level data flow language Pig Latin that is optimized, extensible and easy to use. The most outstanding feature of Pig programs is that their structure is open to considerable parallelization making it easy for handling large data set.

6.HIVE:
Hive developed by Facebook is a data warehouse built on top of Hadoop and provides a simple language known as HiveQL similar to SQL for querying, data summarization and analysis. Hive makes querying faster through indexing.

7.HBASE:
HBase is a column-oriented database that uses HDFS for underlying storage of data. HBase supports random reads and also batch computations using MapReduce. With HBase NoSQL database enterprise can create large tables with millions of rows and columns on hardware machine. The best practice to use HBase is when there is a requirement for random ‘read or write’ access to big datasets.



Q3-Eplain the reasons to learn Big data technologies.

answer:

1.In the last decade,there has been an explosion of data owing to the rise of smart phones,social media,high speed internet etc.
2.Before this phase, the data stored in databases was only transactional data.It was not viewed as an asset.
3.But as said by a leading industrialist,data is the "new oil",organizations have realized that existing data can be analyzed to derive useful insights and make better decisions.
4.But to carry out this task,there are 2 underlying challenges- storage and processing power.
5.Technologies like Hadoop provide the solution to meet these challenges.
6.An entire new field of data sciences has been created owing to big data.
7.Organizations are rapidly investing in these technologies but there is shortage of talent.
8.So Big Data offers exciting career opportunities and also chance to work with cutting edge technologies to make the world a better place.


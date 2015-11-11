# CSCI 5828 – Fall 2015

## Presentation3 - HBase

## Kaiyue An

### Relation between HBase and the field of software engineering?

HBase is the Hadoop database, a distributed, scalable, big data store. Database technology and software engineering are related in a number of ways. First, software engineering methods and tools have to be used for the construction of software providing database functionality and for the development of database applications. Furthermore, special-purpose software engineering tools and techniques have been developed, for example, in data modeling and implementation of persistent application components. Second, database technology may support through ap- propriate services the activities, tools, and techniques in- volved in software development processes. This relation- ship is the focus of the present paper.

### Why software developers care about this topic?

Hadoop can perform only batch processing, and data will be accessed only in a sequential manner. That means one has to search the entire dataset even for the simplest of jobs.

A huge dataset when processed results in another huge data set, which should also be processed sequentially. At this point, a new solution is needed to access any point of data in a single unit of time (random access).

HBase is a distributed column-oriented database built on top of the Hadoop file system. It is an open-source project and is horizontally scalable.

HBase is a data model that is similar to Google’s big table designed to provide quick random access to huge amounts of structured data. It leverages the fault tolerance provided by the Hadoop File System (HDFS).

It is a part of the Hadoop ecosystem that provides random real-time read/write access to data in the Hadoop File System.

One can store the data in HDFS either directly or through HBase. Data consumer reads/accesses the data in HDFS randomly using HBase. HBase sits on top of the Hadoop File System and provides read and write access.
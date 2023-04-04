# Apache-Kafka
<h3>Apache Kafka<h3>
<h6>
Apache Kafka distributed event store and open-source stream-processing platform developed by LinkedIn and donated to the Apache Software Foundation.
Technically speaking, Kafka can process a large amount of data in a short amount of time. It also has low latency, making it possible to process data in real-time. Although Apache Kafka is written in Scala and Java, it may be used with a variety of different programming languages.
<h6>

<h3>Kafka use cases<h3>
<h6>
There are number of ways in which Kafka can be used in any architecture. This section
discusses some of the popular use cases for Apache Kafka and the well-known companies
that have adopted Kafka. The following are the popular Kafka use cases:
<h6>
Log aggregation:
This is the process of collecting physical log files from servers and
putting them in a central place (a file server or HDFS) for processing. Using Kafka
provides clean abstraction of log or event data as a stream of messages, thus taking
away any dependency over file details. This also gives lower-latency processing and
support for multiple data sources and distributed data consumption.
<h6>
Stream processing: Kafka can be used for the use case where collected data
undergoes processing at multiple stages—an example is raw data consumed from
topics and enriched or transformed into new Kafka topics for further consumption.
Hence, such processing is also called stream processing.

Commit logs: Kafka can be used to represent external commit logs for any large
scale distributed system. Replicated logs over Kafka cluster help failed nodes to
recover their states.

Click stream tracking: Another very important use case for Kafka is to capture user
click stream data such as page views, searches, and so on as real-time publish subscribe feeds. This data is published to central topics with one topic per activity
type as the volume of the data is very high. These topics are available for
subscription, by many consumers for a wide range of applications including real-time
processing and monitoring.

Messaging: Message brokers are used for decoupling data processing from data
producers. Kafka can replace many popular message brokers as it offers better
throughput, built-in partitioning, replication, and fault-tolerance.

<h3>Kafka has five main components:<h3>
<h6>
Topic: A topic is a category or feed name to which messages are published by the
message producers. In Kafka, topics are partitioned and each partition is represented
by the ordered immutable sequence of messages. A Kafka cluster maintains the
partitioned log for each topic. Each message in the partition is assigned a unique
sequential ID called the offset.
<h6>
<h6>
Broker: A Kafka cluster consists of one or more servers where each one may have
one or more server processes running and is called the broker. Topics are created
within the context of broker processes.
<h6>
Zookeeper: . Zookeeper is resource manager. ZooKeeper serves as the coordination interface between the Kafka
broker and consumers.
<h6>
Producers: Producers publish data to the topics by choosing the appropriate partition
within the topic. For load balancing, the allocation of messages to the topic partition
can be done in a round-robin fashion or using a custom defined function.
<h6>
Consumer: Consumers are the applications or processes that subscribe to topics and
process the feed of published messages.
<h6>

<h3>features of Kafka<h3>
<h6>
Kafka is a messaging system built for high throughput and fault tolerance.<br>
Kafka has a built-in partition system known as a Topic.<br>
Kafka Includes a replication feature as well.<br>
Kafka provides a queue that can handle large amounts of data and move messages from one sender to another.<br>
Kafka can also save the messages to storage and replicate them across the cluster.<br>
For coordination and synchronization with other services, Kafka collaborates with Zookeeper.<br>
Apache Spark is well supported by Kafka<br>
<h6><br>
<h3>Online Documentation<h3>
<h6>
You can find the latest Spark documentation, including a programming guide, on the project web page. This README file only contains basic explanation.<br>
https://kafka.apache.org/
</h6>

# What is big data?
The basic definition of big data is data that contains greater variety, arriving in increasing volumes and with more velocity.
The means of big is not only about the volume of data. Big means volume, shape-shifting and variety of the data. 

 - **Structured:** Certain rows and columns like database
 - **Semi-structured:** Every data can have different features(columns). They don't have to be the same struct. E.g. xml, json, csv etc. Also used in No-sql DB.
 - **Unstructured:** Image, audio, video etc.

## Usage areas of big data

 - Social media data
 - Mobile phones data
 - Sensor data (IoT devices etc.)
 - Log data
 - Real time data analysis

  
>Big data pipeline:

![Big data pipeline](https://github.com/koyuboy/Big-Data-101/blob/main/images/Big%20data%20pipeline.png)

>5V rule: Big data must contain at least one of this rules.

![5V rule](https://github.com/koyuboy/Big-Data-101/blob/main/images/5V%20rule%20of%20big%20data.png)

# Big data ecosystem

 - **Hadoop** 
	 - We have a master machine and a lot of slave (worker) machines.
	 - Machines are connected to each other parallelly and it's called **cluster**
	 - *HDFS*: Stores files by dividing them into blocks.
	 - *MapReduce*: It processes files by dividing them into blocks.

 - **Apache Spark**
	 - Analyzes big data with distributed processing.
	 - Spark works in-memory so don't need a storage unit.
	 - Performs data analysis on ram.
	 - Apache Spark Core has different modules. Spark SQL, Spark Streaming, MLlib(machine learning), GraphX
 
- **Apache Kafka**
	- Kafka provides us store and analysis to data instantly. It uses Messaging System(Queue) to collect data faultless and fastly.
	- Spark and Hadoop do not take data directly. Data are taken by Kafka firstly. Kafka takes produced data and stores them safely. Then Spark and Hadoop take data (Consume) from Kafka.
- **NoSQL**
	- mongoDB, elasticsearch

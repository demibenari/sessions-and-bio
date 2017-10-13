## Title
### Dumping Time Series Data with Apache Spark

## Session duration

About 45 min

## Video

Scalapeño 2016: Dumping Time Series Data with Spark 

[![Scalapeño 2016: Dumping Time Series Data with Spark  - English](http://img.youtube.com/vi/QuvYj-B3Wec/0.jpg)](http://www.youtube.com/watch?v=QuvYj-B3Wec)

## Slides

- [Slideshre](https://www.slideshare.net/demibenari/scala-like-distributed-collections-dumping-timeseries-data-with-apache-spark) 

## Target audience and level

Data engineers, DevOps engineers, Ops.  
Intermediate level.

- Big Data
- Cloud
- Backend 

## Short Abstract (297 chars)

Vast volumes of data is Time Series, once working with distributed systems your tackling scale and performance problems. 

We'll talk about transformations we’ve made to our data model, review multiple data persistency layers, 

And I’ll try NOT to answer the question “Which one of them is the Best?"

## Long Abstract

Spark RDDs are almost identical to Scala collection, just in a distributed manner, all of the transformations and actions are derived from the Scala collections API.
 
As Martin Odersky mentioned, “Spark - The Ultimate Scala Collections” is the right way to look at RDDs. But with that great distributed power comes a great many data problems: at first you’ll start tackling the concept of partitioning, then the actual data becomes the next thing to worry about.
 
In the talk we’ll go through an overview on Spark's architecture, and see how similar RDDs are to the Scala collections API. We'll then shift to the world of problems that you’ll be facing when using Spark for processing a vast volume of time-series data with multiple data stores (S3, MongoDB, Apache Cassandra, MySQL).
 
When you start tackling many scale and performance problems, many questions arise:
> - How to handle missing data?
> - Should the system handle both serving and backend processes,     or should we separate them out? 
> - Which solution is cheaper? 
> - How do we get the best performance for money spent?
 
In the talk we will tell the tale of all of the transformations we’ve made to our data and review the multiple data persistency layers... and I’ll try my best NOT to answer the question “which persistency layer is the best?” but I do promise to share our pains and lessons learned!

## Talk's Headline Photo

![alt text]( "None")

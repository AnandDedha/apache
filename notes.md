# Apache Kafka

What is Apache kafka ?
 What is Apache Kafka?
If you enter the Kafka website, you’ll find the definition of it right on the first page:

A distributed streaming platform

What is an “A distributed streaming platform”? First, we need to define what is a stream. For that, I have a definition that made me really understand it: Streams are just infinite data, data that never end. It just keeping arriving, and you can process it in real-time.

And distributed? Distributed means that Kafka works in a cluster, each node in the cluster is called Broker. Those brokers are just servers executing a copy of apache Kafka.

So, basically, Kafka is a set of machines working together to be able to handle and process real-time infinite data.



Lets To understand where the need for Apache Kafka is coming from, we'll look at an example of a product.

our new architecture must allow the product to rely on real-time events, where users don't have to wait till tomorrow to get meaningful recommendations based on their latest purchases.

And this is a lot to ask. Introducing such processing of events is an immensely high volume operation and needs to be resistant to failures.

Lucky for us, these are exactly the challenges with which Apache Kafka can help. Apache Kafka is great at untangling data flows, simplifying the way we handle real time data and decouple subsystems.


how it works ?

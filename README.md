# kafka-docker

A local Apache Kafka 4.x cluster on Docker Compose: **3 brokers + 1 KRaft controller**.

> Kafka 4.x dropped ZooKeeper support completely — there are no `zookeeper-*` scripts left
> in the `apache/kafka` image and brokers cannot talk to a ZooKeeper ensemble. The metadata
> role is filled by a dedicated KRaft controller node instead.

# :biking_woman::whale: Distribute log

## Stack

- [Fluentd](https://docs.fluentd.org/v1.0) for unified logging inside Docker containers
- [Apache Kafka](http://kafka.apache.org/documentation/) as a persistent store and streaming pipe
- [Kafka Connect](https://docs.confluent.io/current/connect/index.html) to route logs
- [ElasticSearch](https://www.elastic.co/guide/index.html) for real time indexing and search

## Getting Started

```sh
docker-compose up
```

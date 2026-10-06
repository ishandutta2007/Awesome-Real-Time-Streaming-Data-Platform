# Awesome-Real-Time-Streaming-Data-Platform

## Top Real-Time Streaming Data Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Event Streaming, Message Brokers & Self-Hosted Data Backbones*  

**Last updated: October 2026**



This repository tracks notable **commercial real-time streaming data platforms** and **open-source projects** that ingest, buffer, and distribute continuous data streams — powering event-driven architectures, real-time analytics, and data pipelines.



**Examples** include Amazon Kinesis, Apache Kafka, Confluent Cloud, Redpanda Cloud, Azure Event Hubs, Google Cloud Pub/Sub, StreamNative (Apache Pulsar), Aiven for Kafka, Decodable, and Upstash (the category leaders).



**Open-source emphasis**: Real-time streaming data is one of the strongest open-source domains. **Apache Kafka** anchors event streaming, **Redpanda** brings C++ performance, **Apache Pulsar** adds multi-tenancy, and **NATS** provides cloud-native messaging. **Apache Flink**, **Kafka Streams**, and **ksqlDB** handle stream processing. **Debezium** powers CDC, while **Benthos** and **Vector** handle data pipelines. **Apache RocketMQ** and **NSQ** serve specialized workloads. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Kinesis](https://aws.amazon.com/kinesis/)**  

  **AWS's real-time streaming data service** — ingest, buffer, and process data streams at scale . **Kinesis Data Streams, Firehose, Analytics, and Video Streams** . **Best for AWS-native streaming** .



- **[Confluent Cloud](https://www.confluent.io/confluent-cloud/)**  

  **The leading managed Kafka platform** — fully managed Kafka, ksqlDB, Flink, connectors, and schema registry . **The enterprise standard for event streaming** . **Best for organizations wanting Kafka without operational burden** .



- **[Redpanda Cloud](https://redpanda.com/)**  

  **Kafka-compatible streaming platform in C++** — no Zookeeper, no JVM . **10x faster than Kafka** in some benchmarks . **Best for high-performance streaming** .



- **[Azure Event Hubs](https://azure.microsoft.com/en-us/products/event-hubs/)**  

  **Azure's big data streaming platform** — millions of events per second . **Event Hubs Capture** for automatic data loading . **Best for Azure-native streaming** .



- **[Google Cloud Pub/Sub](https://cloud.google.com/pubsub)**  

  **Google's asynchronous messaging service** — global scale with at-least-once delivery . **Best for GCP-native streaming** .



- **[StreamNative Cloud](https://streamnative.io/)**  

  **Managed Apache Pulsar and Flink** — multi-tenancy and geo-replication . **Best for Pulsar deployments** .



- **[Aiven for Kafka](https://aiven.io/kafka)**  

  **Managed Kafka on multiple clouds** — open-source data platform . **Best for multi-cloud Kafka** .



- **[Decodable](https://www.decodable.co/)**  

  **Managed stream processing** — SQL-based pipelines on Apache Flink . **Best for simple streaming ETL** .



- **[Upstash](https://upstash.com/)**  

  **Serverless Redis and Kafka** — pay-per-request messaging . **Best for serverless streaming** .



## Open-Source GitHub Projects



### Event Streaming Platforms



- **[Apache Kafka](https://github.com/apache/kafka)**  

  **The de facto standard for event streaming**, Apache-2.0 licensed with **28,000+ GitHub stars** . **Distributed, fault-tolerant, high-throughput pub/sub messaging** . **Kafka Connect for source/sink connectors** and **Kafka Streams for stream processing** . **The foundation for most real-time data architectures** . **Best for enterprise event streaming at scale** .



- **[Redpanda](https://github.com/redpanda-data/redpanda)**  

  **Kafka-compatible streaming platform in C++**, BSL licensed (free for most uses) . **No Zookeeper, no JVM** — simpler operations . **10x faster than Kafka** in some benchmarks . **Best for teams wanting Kafka compatibility with better performance** .



- **[Apache Pulsar](https://github.com/apache/pulsar)**  

  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **14,000+ GitHub stars** . **Multi-tenancy, geo-replication, and tiered storage** . **The main alternative to Kafka** . **Best for multi-tenant and geo-distributed streaming** .



- **[NATS](https://github.com/nats-io/nats-server)**  

  **Cloud-native messaging system**, Apache-2.0 licensed . **Lightweight, high-performance pub/sub** with JetStream for persistence . **Best for IoT and edge streaming** .



- **[Apache RocketMQ](https://github.com/apache/rocketmq)**  

  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Low-latency, high-throughput with transactional messages** . **Best for e-commerce and financial services** .



- **[NSQ](https://github.com/nsqio/nsq)**  

  **Real-time distributed messaging platform**, MIT licensed with **12,000+ GitHub stars** . **Simple, reliable, and scalable** . **Best for simple messaging at scale** .



### Stream Processing



- **[Apache Flink](https://github.com/apache/flink)**  

  **The de facto standard for stateful stream processing**, Apache-2.0 licensed with **24,000+ GitHub stars** . **Exactly-once semantics, event-time processing, and savepoints** . **Best for mission-critical stream processing** .



- **[Apache Spark Structured Streaming](https://github.com/apache/spark)**  

  **Unified batch and stream processing**, Apache-2.0 licensed . **Micro-batch with exactly-once semantics** . **Best for teams already using Spark** .



- **[Kafka Streams](https://github.com/apache/kafka)**  

  **Stream processing library for Kafka**, Apache-2.0 licensed . **No separate cluster** — runs in your application . **Best for Kafka-native stream processing** .



- **[ksqlDB](https://github.com/confluentinc/ksql)**  

  **Streaming SQL for Kafka**, Confluent Community License . **SQL interface for Kafka Streams** . **Best for SQL-proficient teams** .



- **[Apache Beam](https://github.com/apache/beam)**  

  **Unified programming model for batch and stream**, Apache-2.0 licensed . **Portable across Flink, Spark, Dataflow, and Samza** . **Best for portable pipelines** .



### Data Movement & CDC



- **[Debezium](https://github.com/debezium/debezium)**  

  **The leading open-source CDC platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Captures row-level changes from databases** . **Best for database replication and real-time sync** .



- **[Benthos (Redpanda Connect)](https://github.com/redpanda-data/connect)**  

  **Stream processing without code**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Declarative YAML configuration for streaming ETL** . **Best for data engineers wanting stream pipelines without programming** .



- **[Vector](https://github.com/vectordotdev/vector)**  

  **High-performance observability data pipeline**, MPL-2.0 licensed with **18,000+ GitHub stars** . **Collect, transform, and route logs, metrics, and events** . **Best for observability data** .



- **[Apache NiFi](https://github.com/apache/nifi)**  

  **Open-source data flow automation**, Apache-2.0 licensed . **Visual programming for data routing and transformation** . **Best for data flow management** .



- **[Kafka Connect](https://github.com/apache/kafka)**  

  **Source/sink connectors for Kafka**, Apache-2.0 licensed . **200+ connectors** . **Best for data integration** .



### Additional Strong Open-Source Options



- **Apache Samza** — Stream processing on Kafka .

- **Apache Storm** — Real-time computation (legacy) .

- **Apache Heron** — Twitter's stream processing (retired) .

- **Apache Apex** — Enterprise stream processing (retired) .

- **Apache Flume** — Log aggregation (legacy) .

- **Logstash** — Data collection and transformation .

- **Fluentd** — Unified logging layer .

- **Fluent Bit** — Lightweight log processor .

- **Embulk** — Pluggable bulk data loader .

- **Apache SeaTunnel** — High-performance data integration .



**Frameworks for building custom real-time streaming data solutions**: Combine **Apache Kafka** or **Redpanda** for high-throughput event streaming . Use **NATS** for lightweight, cloud-native messaging . Deploy **Apache Flink** for stateful stream processing . Choose **Debezium** for CDC from databases . Integrate **Benthos** or **Vector** for code-free pipelines and observability data . Use **ksqlDB** for SQL-based stream processing . Note that true managed streaming data platforms with global infrastructure, automatic scaling, and vendor-supported SLAs (Confluent Cloud, Amazon Kinesis, Azure Event Hubs) remain primarily commercial territory; open-source stacks provide strong event streaming, stream processing, and data movement foundations that require integration for complete real-time data platforms.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Real-time streaming platforms handle high-volume data in motion. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: Redpanda uses BSL (free for most uses but not OSI), ksqlDB uses Confluent Community License, and NATS uses Apache-2.0. Verify licensing against your use case before committing .

- **Exactly-once semantics are hard** — Kafka, Pulsar, and NATS JetStream each handle delivery guarantees differently. Understand your requirements before choosing .

- **Event ordering matters** — Kafka guarantees order per partition; other systems may not. Design for idempotency and handle out-of-order events .

- The open-source ecosystem provides strong event streaming, stream processing, and data movement foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for data engineers, platform teams, and organizations seeking streaming data sovereignty.**  

Let's make real-time streaming data platforms more open, transparent, and reliable.

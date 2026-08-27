<p align="center">
  <br>
  <img width="400" src="./awesome%20kafka.png" alt="logo of kafka-awesome repository">
  <br>
  <br>
</p>

# Awesome Kafka with stars

> A curated list of awesome things related to Apache Kafka.

## Contents

* [Libraries](#libraries)
  * [Kafka](#kafka)
  * [Kafka UI](#kafka-ui)
  * [Kafka Streams](#kafka-streams)
  * [Kafka Connect](#kafka-connect)
  * [REST Proxy](#rest-proxy)
  * [KSQL](#ksql)
  * [Schema Registry](#schema-registry)
  * [Other Awesome Kafka](#other-awesome-kafka)
  * [Kafkaesque](#kafkaesque)
* [Resources](#resources)
  * [Learning](#learning)
  * [Blogs](#blogs)
  * [Books](#books)

<!-- md-parser-start -->

## Libraries

### Kafka

* [sarama](https://github.com/Shopify/sarama) ⭐ 12,510 | 🐛 33 | 🌐 Go | 📅 2026-08-25 - Sarama is an MIT-licensed Go client library for Apache Kafka version 0.8 (and later).
* [Kafka Manager](https://github.com/yahoo/kafka-manager) ⭐ 11,925 | 🐛 522 | 🌐 Scala | 📅 2023-08-02 - Web-based tool for managing a Kafka cluster.
* [Strimzi](https://github.com/strimzi/strimzi-kafka-operator) ⭐ 5,917 | 🐛 154 | 🌐 Java | 📅 2026-08-27 - Operator for deploying and running Apache Kafka on Kubernetes and OpenShift.
* [kafkacat](https://github.com/edenhill/kafkacat) ⭐ 5,778 | 🐛 162 | 🌐 C | 📅 2024-07-09 - Generic command line non-JVM Apache Kafka producer and consumer.
* [jocko](https://github.com/travisjeffery/jocko) ⭐ 5,012 | 🐛 64 | 🌐 Go | 📅 2026-05-20 - Kafka implemented in Golang with built-in coordination (No ZK dep, single binary install, Cloud Native).
* [Burrow](https://github.com/linkedin/Burrow) ⭐ 3,963 | 🐛 250 | 🌐 Go | 📅 2026-08-21 - Kafka Consumer Lag Checking.
* [kafkahq](https://github.com/tchiotludo/kafkahq) ⭐ 3,849 | 🐛 285 | 🌐 Java | 📅 2026-08-24 - Kafka GUI for topics, topics data, consumers group, schema registry, connect and more.
* [kafka-eagle](https://github.com/smartloli/kafka-eagle) ⭐ 3,179 | 🐛 224 | 🌐 Java | 📅 2025-12-18 - Used to monitor the consumer status of Kafka clusters, as well as offsets, metadata and other information.
* [cruise-control](https://github.com/linkedin/cruise-control) ⭐ 3,043 | 🐛 288 | 🌐 Java | 📅 2026-08-17 - Cruise-control is the first of its kind to fully automate the dynamic workload rebalance and self-healing of a kafka cluster.
* [spring-kafka](https://github.com/spring-projects/spring-kafka) ⭐ 2,498 | 🐛 38 | 🌐 Java | 📅 2026-08-26
* [kafka-monitor](https://github.com/linkedin/kafka-monitor) ⭐ 2,064 | 🐛 33 | 🌐 Java | 📅 2025-03-09
* [secor](https://github.com/pinterest/secor) ⭐ 1,856 | 🐛 269 | 🌐 Java | 📅 2026-03-10 - Secor is a service implementing Kafka log persistence.
* [reactive-kafka](https://github.com/akka/reactive-kafka) ⭐ 1,422 | 🐛 112 | 🌐 Scala | 📅 2026-08-27 - Alpakka Kafka connector - Alpakka is a Reactive Enterprise Integration library for Java and Scala, based on Reactive Streams and Akka.
* [kt](https://github.com/fgeller/kt) ⭐ 955 | 🐛 11 | 🌐 Go | 📅 2024-04-08 - Kafka command line tool.
* [uReplicator](https://github.com/uber/uReplicator) ⭐ 936 | 🐛 78 | 🌐 Java | 📅 2023-12-16 - Improvement of Apache Kafka Mirrormaker.
* [hermes](https://github.com/allegro/hermes) ⭐ 865 | 🐛 7 | 🌐 Java | 📅 2026-08-18 - Fast and reliable message broker built on top of Kafka.
* [kafka-pixy](https://github.com/mailgun/kafka-pixy) ⭐ 789 | 🐛 17 | 🌐 Go | 📅 2024-04-23 - Kafka-Pixy is a dual API (gRPC and REST) proxy for Kafka with automatic consumer group control.
* [topicctl](https://github.com/segmentio/topicctl) ⭐ 666 | 🐛 33 | 🌐 Go | 📅 2026-06-25 - A tool for easy, declarative management of Kafka topics. Includes the ability to "apply" topic changes from YAML as well as a repl for interactive exploration of brokers, topics, consumer groups, messages, and more.
* [chaperone](https://github.com/uber/chaperone) ⚠️ Archived - A Kafka audit system.
* [kafka-spark-consumer](https://github.com/dibbhatt/kafka-spark-consumer) ⭐ 631 | 🐛 3 | 🌐 Java | 📅 2026-04-24
* [dockerkafka](https://github.com/pinterest/doctorkafka) ⚠️ Archived - DoctorKafka is a service for Kafka cluster auto healing and workload balancing.
* [kafka-tools](https://github.com/linkedin/kafka-tools) ⭐ 598 | 🐛 24 | 🌐 Python | 📅 2022-01-24 - A collection of tools for working with Apache Kafka.
* [kasper](https://github.com/movio/kasper) ⚠️ Archived - Kasper is a lightweight library for processing Kafka topics.
* [schema-registry-ui](https://github.com/landoop/schema-registry-ui) ⭐ 425 | 🐛 40 | 🌐 JavaScript | 📅 2024-02-13 - Web tool for Avro Schema Registry.
* [kareldb](https://github.com/rayokota/kareldb) ⭐ 389 | 🐛 12 | 🌐 Java | 📅 2025-10-15 - A Relational Database Backed by Apache Kafka.
* [Decaton](https://github.com/line/decaton) ⭐ 373 | 🐛 20 | 🌐 Java | 📅 2026-06-19 - High throughput asynchronous task processing framework
* [kafka-websocket](https://github.com/b/kafka-websocket) ⭐ 353 | 🐛 12 | 🌐 Java | 📅 2023-12-16
* [Yelp kafka-utils](https://github.com/Yelp/kafka-utils) ⚠️ Archived
* [kafka-streams-cep](https://github.com/fhussonnois/kafkastreams-cep) ⭐ 315 | 🐛 6 | 🌐 Java | 📅 2023-12-16 - Complex Event Processing on top of Kafka Streams.
* [kcache](https://github.com/rayokota/kcache) ⭐ 260 | 🐛 18 | 🌐 Java | 📅 2025-12-29 - An In-Memory Cache Backed by Apache Kafka.
* [mirus](https://github.com/salesforce/mirus) ⭐ 210 | 🐛 28 | 🌐 Java | 📅 2026-08-05 - Mirus is a cross data-center data replication tool for Apache Kafka.
* [sangrenel](https://github.com/jamiealquiza/sangrenel) ⚠️ Archived
* [kafka-unit](https://github.com/chbatey/kafka-unit) ⭐ 176 | 🐛 24 | 🌐 Java | 📅 2021-11-04
* [Strimzi Kafka CLI](https://github.com/systemcraftsman/strimzi-kafka-cli) ⭐ 91 | 🐛 30 | 🌐 Python | 📅 2026-08-13 - A CLI for Strimzi Kafka Operator.
* [Kafka Cluster Kraft Mode - DockerCompose](https://github.com/minhhungit/kafka-kraft-cluster-docker-compose) ⭐ 24 | 🐛 1 | 🌐 C# | 📅 2024-08-01 - Workable kafka cluster with kraft mode using docker-compose.
* [kafka-lag-based-assignor](https://github.com/grantneale/kafka-lag-based-assignor) ⭐ 13 | 🐛 5 | 🌐 Java | 📅 2020-10-13 - Kafka partition assignor that distributes lag evenly across a consumer group.
* [ksql-machine-learning-udf](https://github.com/kaiwaehner/ksql-machine-learning-udf) ⭐ 11 | 🐛 0 | 🌐 Java | 📅 2018-03-26
* [kafka-jackson](https://github.com/jcustenborder/kafka-jackson) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2018-04-14 - Kafka Serializer, Deserializer, and Serde for Jackson JSON.
* [kafkabeat](https://github.com/dearcode/kafkabeat) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2017-09-12 - Elasticsearch Beats for kafka.
* [kadeck](https://www.xeotek.com/kadeck/) - Apache Kafka Monitoring, Kafka UI and data platform for Desktop or Web.
* [conduktor](https://www.conduktor.io/)

### Kafka UI

* [Kafdrop](https://github.com/obsidiandynamics/kafdrop) ⭐ 6,153 | 🐛 46 | 🌐 Java | 📅 2026-08-27 - Web UI for browsing Kafka topics and consumer groups.
* [kowl](https://github.com/cloudhut/kowl) ⭐ 4,325 | 🐛 154 | 🌐 TypeScript | 📅 2026-08-27
* [kafka-topics-ui](https://github.com/lensesio/kafka-topics-ui) ⭐ 875 | 🐛 14 | 🌐 JavaScript | 📅 2022-02-17
* [kafka-connect-ui](https://github.com/landoop/kafka-connect-ui) ⭐ 519 | 🐛 28 | 🌐 JavaScript | 📅 2025-05-07 - Web tool for Kafka Connect.
* [kafka-webview](https://github.com/SourceLabOrg/kafka-webview) ⭐ 393 | 🐛 59 | 🌐 Java | 📅 2025-07-13
* [cruise-control-ui](https://github.com/linkedin/cruise-control-ui) ⭐ 375 | 🐛 25 | 🌐 Vue | 📅 2024-08-20
* [kafka-view](https://github.com/fede1024/kafka-view) ⭐ 224 | 🐛 20 | 🌐 Rust | 📅 2022-09-01
* [tsujun](https://github.com/matsumana/tsujun) ⚠️ Archived - Yet another Web UI for KSQL.
* [real-time-ui-with-kafka-streams](https://github.com/lucasjellema/real-time-ui-with-kafka-streams) ⭐ 32 | 🐛 1 | 🌐 Java | 📅 2017-10-03
* [KafkaTrail](https://github.com/imkrishnaagrawal/KafkaTrail) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2024-06-02
* [akhq](https://akhq.io)

### Kafka Streams

* [schema-registry-ui](https://github.com/lensesio/schema-registry-ui) ⭐ 425 | 🐛 40 | 🌐 JavaScript | 📅 2024-02-13
* [winton-kafka-streams](https://github.com/wintoncode/winton-kafka-streams) ⚠️ Archived - A Python implementation of Apache Kafka Streams.
* [kafka-operator](https://github.com/krallistic/kafka-operator) ⚠️ Archived
* [mockedstreams](https://github.com/jpzk/mockedstreams) ⭐ 186 | 🐛 7 | 🌐 Scala | 📅 2021-01-16
* [kafkabalancer](https://github.com/CAFxX/kafkabalancer) ⭐ 47 | 🐛 1 | 🌐 Go | 📅 2017-11-14
* [kafka-streams-consumer-offsets-to-json](https://github.com/sderosiaux/kafka-streams-consumer-offsets-to-json) ⭐ 13 | 🐛 2 | 🌐 Scala | 📅 2019-10-18 - A Kafka Streams process to convert consumer\_offsets to a JSON-readable topic.

### Kafka Connect

* [Maxwell](https://github.com/zendesk/maxwell) ⭐ 4,258 | 🐛 266 | 🌐 Java | 📅 2026-08-13
* [kafka-connect-file-pulse](https://github.com/streamthoughts/kafka-connect-file-pulse) ⭐ 350 | 🐛 49 | 🌐 Java | 📅 2026-06-26 - A polyvalent, scalable and reliable, Kafka Connector that makes it easy to parse, transform and stream any file, in any format, into Apache Kafka.
* [snowflake-kafka-connector](https://github.com/snowflakedb/snowflake-kafka-connector) ⭐ 176 | 🐛 51 | 🌐 Java | 📅 2026-08-24
* [kafka-connect-transform-common](https://github.com/jcustenborder/kafka-connect-transform-common) ⭐ 175 | 🐛 25 | 🌐 Java | 📅 2026-07-08 - Common Transforms for Kafka Connect.
* [kafka-connect-mq-source](https://github.com/ibm-messaging/kafka-connect-mq-source) ⭐ 108 | 🐛 13 | 🌐 Java | 📅 2026-07-22
* [kafka-connect-protobuf-converter](https://github.com/blueapron/kafka-connect-protobuf-converter) ⚠️ Archived - Protobuf converter plugin for Kafka Connect.
* [aiven-kafka-connect-transforms](https://github.com/aiven/aiven-kafka-connect-transforms) ⭐ 89 | 🐛 12 | 🌐 Java | 📅 2026-08-01 - A collection of Single Message Transformations (SMTs) for Kafka Connect.
* [kafka-connect-client](https://github.com/SourceLabOrg/kafka-connect-client) ⭐ 41 | 🐛 10 | 🌐 Java | 📅 2025-06-26 - A kafka-connect REST api client for java.
* [toketi-kafka-connect-iohub](https://github.com/Azure/toketi-kafka-connect-iothub) ⚠️ Archived
* [kafka-connect-jenkins](https://github.com/yaravind/kafka-connect-jenkins) ⭐ 31 | 🐛 14 | 🌐 Java | 📅 2022-11-15
* [kafka-connect-http](https://github.com/thomaskwscott/kafka-connect-http) ⭐ 30 | 🐛 9 | 🌐 Java | 📅 2022-07-07
* [connectctl](https://github.com/90poe/connectctl) ⭐ 14 | 🐛 8 | 🌐 Go | 📅 2025-12-05 - Manage kafka connect connectors easily.
* [kafka-connect-transformers](https://github.com/Landoop/kafka-connect-transformers) ⚠️ Archived
* [Apache Camel Kafka Connect](https://camel.apache.org/camel-kafka-connector/latest/index.html) - 340+ Apache Camel components as Kafka Connect connectors.
* [Confluent Connector Hub](https://www.confluent.io/product/connectors/)

### REST Proxy

* [Zilla](https://github.com/aklivity/zilla) ⭐ 1,710 | 🐛 225 | 🌐 Java | 📅 2026-08-27 - An API gateway built for event-driven architectures and streaming that supports standard protocols such as HTTP, SSE, gRPC, MQTT and the native Kafka protocol.
* [strimzi-http-bridge](https://github.com/strimzi/strimzi-kafka-bridge) ⭐ 338 | 🐛 14 | 🌐 Java | 📅 2026-08-27 - Strimzi Kafka Bridge (AMQP & HTTP).
* [kafka-rest](https://github.com/confluentinc/kafka-rest) ⭐ 162 | 🐛 276 | 🌐 Java | 📅 2026-08-27 - Confluent REST Proxy.

### KSQL

### Schema Registry

* [schema-registry](https://github.com/confluentinc/schema-registry) ⭐ 2,463 | 🐛 392 | 🌐 Java | 📅 2026-08-27 - Confluent Schema registry for Kafka.
* [apicurio-registry](https://github.com/Apicurio/apicurio-registry) ⭐ 922 | 🐛 638 | 🌐 Java | 📅 2026-08-27 - Apicurio API/schema registry (includes UI).
* [ksql-jdbc-driver](https://github.com/mmolimar/ksql-jdbc-driver) ⭐ 87 | 🐛 14 | 🌐 Scala | 📅 2022-04-01
* [ballerina-schema-registry](https://github.com/ballerina-platform/module-ballerinax-confluent.cregistry) ⭐ 2 | 🐛 3 | 🌐 Ballerina | 📅 2026-07-03 - Ballerina Confluent Schema Registry

### Other Awesome Kafka

* [infoslack/awesome-kafka](https://github.com/infoslack/awesome-kafka) ⭐ 591 | 🐛 2 | 📅 2026-05-05
* [dharmeshkakadia/awesome-kafka](https://github.com/dharmeshkakadia/awesome-kafka) ⭐ 209 | 🐛 2 | 📅 2026-08-06
* [ApacheKafka](https://github.com/jsroyal/ApacheKafka) ⭐ 36 | 🐛 1 | 📅 2023-12-07
* [ballerina-avro-kafka-serializer](https://github.com/ballerina-platform/module-ballerinax-confluent.cavroserdes) ⭐ 2 | 🐛 0 | 🌐 Ballerina | 📅 2026-05-04 - Ballerina Confluent Avro Serializer/Deserializer
* [awesome-kafka-playground](https://github.com/anascotti/awesome-kafka-playground) ⭐ 1 | 🐛 0 | 🌐 Java | 📅 2018-05-22

### Kafkaesque

* [Pulsar](https://github.com/apache/incubator-pulsar) ⭐ 15,316 | 🐛 1,738 | 🌐 Java | 📅 2026-08-27
* [faust](https://github.com/robinhood/faust) ⭐ 6,825 | 🐛 279 | 🌐 Python | 📅 2024-07-27 - Python Stream Processing.
* [Chronicle-Queue](https://github.com/OpenHFT/Chronicle-Queue) ⭐ 3,799 | 🐛 45 | 🌐 Java | 📅 2026-08-27
* [Heron](https://github.com/apache/incubator-heron) ⚠️ Archived
* [CorfuDB](https://github.com/CorfuDB/CorfuDB) ⭐ 665 | 🐛 201 | 🌐 Java | 📅 2026-08-27
* [Meteor](https://github.com/obsidiandynamics/meteor) ⭐ 24 | 🐛 0 | 🌐 Java | 📅 2022-07-25 - Lightweight, broker-less alternative to Kafka for message streaming.
* [Flink](https://flink.apache.org/)
* [Spark](https://spark.apache.org/)
* [Beam](https://beam.apache.org/)
* [Arrow](https://arrow.apache.org/)
* [Samza](https://samza.apache.org/)
* [Nats](https://nats.io/)
* [GenStage](https://hexdocs.pm/gen_stage/GenStage.html)
* [redpanda](https://vectorized.io/)
* [Bufstream](https://buf.build/product/bufstream) - Store directly to Apache Iceberg™ tables and guarantee data quality with Bufstream, a drop-in replacement for Apache Kafka®.

## Resources

### Learning

* [Passionate Developer: Kafka Streams DSL vs processor API](https://mkuthan.github.io/blog/2017/11/02/kafka-streams-dsl-vs-processor-api/)
* [Mastering Kafka Streams](https://jaceklaskowski.gitbooks.io/mastering-kafka-streams)
* [Spark Streaming + Kafka Integration Guide](https://spark.apache.org/docs/latest/streaming-kafka-integration.html)

### Blogs

* [CodingJunkie](http://codingjunkie.net/) - Random Thoughts on Coding by Bill Bejeck.
* [Understanding Kafka with Factorio](\[https://ruurtjan.com/articles/understanding-kafka-with-factorio)

### Books

* [Kafka Streams in Action](https://www.manning.com/books/kafka-streams-in-action)
* [Kafka in Action](https://www.manning.com/books/kafka-in-action)
* [Kafka the Definitive Guide](https://shop.oreilly.com/product/0636920044123.do)
* [Streaming Data Pipelines with Kafka](https://www.manning.com/books/streaming-data-pipelines-with-kafka)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._

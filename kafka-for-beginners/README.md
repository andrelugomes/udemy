https://github.com/simplesteph/kafka-beginners-course

https://app.bonsai.io/clusters

https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/java-rest-high-getting-started-maven.html

```bash
 bin/zookeeper-server-start.sh config/zookeeper.properties
```

```bash
 bin/kafka-server-start.sh config/server.properties 
```

```bash
 bin/kafka-topics.sh --zookeeper localhost:2181 --create --topic twitter_tweets --partitions 3 --replication-factor 1
```
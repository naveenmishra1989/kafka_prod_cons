./zookeeper-server-start.sh ../config/zookeeper.properties
Add the below properties in the server.properties
listeners=PLAINTEXT://localhost:9092
auto.create.topics.enable=false  -->disable to auto create topics
Start up the Kafka Broker
./kafka-server-start.sh ../config/server.properties
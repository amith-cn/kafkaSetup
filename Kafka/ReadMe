 docker compose -f docker-compose.yml up -d


Docker ps
docker exec -it {KafkacontainerId}  /bin/sh

cd /opt/bitnami/kafka/bin
./kafka-topics.sh --create --topic {topicName} --bootstrap-server localhost:19092 --replication-factor 1 --partitions 3

Useful Kafka Commands

kafka-console-producer.sh --topic topicB --bootstrap-server localhost:19092
kafka-console-consumer.sh --topic GenAIRequestFindItTopic --from-beginning --bootstrap-server localhost:19092
kafka-console-consumer.sh --bootstrap-server localhost:19092 --topic GenAIResponseFindItTopic --group findit-genai-consumer-group

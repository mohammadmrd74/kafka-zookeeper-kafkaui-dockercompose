# kafka-zookeeper-kafkaui-dockercompose
kafka,zookeeper and kafka-ui docker compose file

export KAFKA_IP=$(docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' kafka1)

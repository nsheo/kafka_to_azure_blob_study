# kafka_to_azure_blob_study

1. 개요

   - Kafka를 통해 Telegraf의 실시간 메트릭 데이터를 Azure Blob Storage 로 전송하기 위한 실습

   - Kafdrop을 사용한 Kafka UI연동

   - Camel-Kafka-Connector를 사용한 kafka 연동

   - Docker-Compose를 통한 간단한 Package화

     

2. 구현 

   1. Kafka / Zookeeper 연동

   2. 구축한 Kafka에서 Internal 프로토콜을 사용하여 Kafdrop 연동

   3. Kafka-connector를 사용하기 위한 노드 구현

      

3. 참조 URL

   - Kafdrop : https://github.com/obsidiandynamics/kafdrop
   - Kafka-docker-compose : https://github.com/bitnami/bitnami-docker-kafka
   - Kafka-connector : https://github.com/scholzj/strimzi-compose-up
   - Camel Kafka Connector : https://camel.apache.org/camel-kafka-connector/latest/connectors/camel-azure-storage-blob-kafka-sink-connector.html
# Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream

1. Téléchargement du KAFKA 
- Démarrer Zookeeper :

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/786d1722-3566-4c21-b267-e631371e71d8)

- Démarrer Kafka-server

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/ddf36b7e-2daa-4da7-b911-c0fe100dfa6c)

- Tester avec Kefka-console-producer et kafka-console-consumer
  
  . Lancer Kafka-console-consumer et kafka-console-producer :
  
![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/0e6cec99-94a4-446f-80ac-9c02d12f0aa6)

2. Avec Docker (voir https://developer.confluent.io/quickstart/kafka-docker/)

 - Créer le fichier docker-compose.yml

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/a22a9b95-cb8c-49dc-8a03-5593806092b0)

 - Démarrer les conteneurs docker : zookeeper et kafka-broker
 ![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/e59a92a9-0eec-482f-b1af-d68fe7aa04e5)

 
 - Tester avec Kafka-console-producer et kafka-console-consumer

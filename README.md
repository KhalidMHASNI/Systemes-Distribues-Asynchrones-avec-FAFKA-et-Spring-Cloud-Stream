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

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/e8b97189-4f5c-4afe-85e8-9bb018b8d6f0)
 
 - Tester avec Kafka-console-producer et kafka-console-consumer
 
 ![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/a598ce60-5820-4c51-a56a-2894ab360be3)
![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/bf03b1ee-2af6-434e-9634-35ed0e10cad8)


3. En Utilisant KAFKA et Stpring Cloud Streams, Créer :

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/c1fc6541-133d-4f5e-b4cc-7d18d796d8de)

- Un Service Producer KAFKA via un Rest Controler

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/f1c67a3f-6e24-4b46-9fb4-1665cc94d074)

- Un Service Consumer KAFKA

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/5d17d190-0a95-4d47-80ef-277a46dd04e4)

- Un Service Supplier KAFKA

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/823a1cd3-fda7-47bd-940e-121c3624814a)

- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/32d77773-d918-4978-9bc5-d6f467289569)

- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

![image](https://github.com/KhalidMHASNI/Systemes-Distribues-Asynchrones-avec-KAFKA-et-Spring-Cloud-Stream/assets/82038554/9b545f79-a531-423e-97be-4fdac11d86af)


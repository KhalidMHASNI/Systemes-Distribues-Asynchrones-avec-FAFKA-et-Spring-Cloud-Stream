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


3. 
En Utilisant KAFKA et Stpring Cloud Streams, Créer :
- Un Service Producer KAFKA via un Rest Controler
- Un Service Consumer KAFKA
- Un Service Supplier KAFKA
- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams
- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

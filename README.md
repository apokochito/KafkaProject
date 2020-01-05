# Apache Kafka

- Install it from Homebrew manager https://medium.com/@Ankitthakur/apache-kafka-installation-on-mac-using-homebrew-a367cdefd273

- Before you run anything, try to configure this first...

  kafka/server.properties > listeners=PLAINTEXT://localhost:9092
  
- If you're getting this message "Error Path:/config/clients Error:KeeperErrorCode = NodeExists for /config/clients (org.apache.zookeeper.server.PrepRequestProcessor)" don't worry about it [Info here](https://stackoverflow.com/questions/43559328/got-user-level-keeperexception-when-processing)
  
1. HelloWorld with Kafka (**helloWorld branch**)
   
   This project is a producer that sends a single message, and a consumer that receives messages and prints them out.
   https://www.javainuse.com/misc/apache-kafka-hello-world
  
    - Steps
      - First step

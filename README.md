# kafka Zookeper Docker image

1 -  docker-compose -f docker-compose.yml up
2 - docker-compose -f docker-compose.yml up -d
3 -  docker ps -> view instance running
4 -  docker exec -it kafka /bin/sh  -> terminal
5 - cd /opt/
6 - cd kafka
7 - cd bin/
8 - ./bin/kafka-topics.sh --create --zookeeper zookeeper:2181 --replication-factor 1 --partitions 1 --topic TopicName
9 -  ./bin/kafka-topics.sh --list --zookeeper zookeeper:2181    -> list all topics
10  
11
12
13

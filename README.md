#### ubuntu download
wget https://ftp.wayne.edu/apache/kafka/2.6.0/kafka_2.13-2.6.0.tgz

#### run
```
bin/zookeeper-server-start.sh config/zookeeper.properties
bin/kafka-server-start.sh config/server.properties
JMX_PORT=8004 bin/kafka-server-start.sh config/server.properties

```

#### more machine
```
sudo nano config/server.properties
listeners=PLAINTEXT://ec2-54-91-38-33.compute-1.amazonaws.com:9092
```

#### kill port
```
sudo lsof -i -P -n | grep LISTEN
kill -9 id
```

##### ubuntu install java
https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04


#### reference
https://www.digitalocean.com/community/tutorials/how-to-install-apache-kafka-on-ubuntu-18-04

https://www.youtube.com/watch?v=jY5fzVCkABg

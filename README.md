#### ubuntu download
wget https://ftp.wayne.edu/apache/kafka/2.6.0/kafka_2.13-2.6.0.tgz


#### kill port
```
kill $(lsof -t -i:9092)
kill $(lsof -t -i:2181)
```

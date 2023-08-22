docker exec broker kafka-topics --bootstrap-server localhost:9092 --list 

docker exec broker kafka-topics --bootstrap-server localhost:9092 --create --topic data --partitions 3 --replication-factor 1

docker exec broker kafka-topics --bootstrap-server localhost:9092 --describe --topic orders 

docker exec broker kafka-topics --bootstrap-server localhost:9092 --delete --topic orders
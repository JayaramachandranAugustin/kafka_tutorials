docker exec kafka kafka-topics --bootstrap-server localhost:8098 --create --topic orders

docker exec --interactive --tty kafka kafka-console-producer --bootstrap-server localhost:8098 --topic orders

docker exec kafka kafka-console-consumer --bootstrap-server localhost:8098 --topic orders --from-beginning
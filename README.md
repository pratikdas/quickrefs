## Starting a web server
To start a webserver run the command below:

```shell
python3 -m http.server
```
That will open a webserver on port 8080. You can then open your browser at http://127.0.0.1:8080/

## Starting MongoDB server
bin/mongod --dbpath /Users/pratikdas//pratik/mongodb --port 12345

bin/mongo --port 12345

## Starting Kafka broker

Download Kafka from https://www.apache.org/dyn/closer.cgi?path=/kafka/3.1.0/kafka_2.13-3.1.0.tgz

Start Zookeeper

```shell
bin/zookeeper-server-start.sh config/zookeeper.properties
```
Start kafka broker

```shell
bin/kafka-server-start.sh config/server.properties
```
## Install Kotlin
brew install kotlin
kotlinc -help
compile application: kotlinc hello.kt -include-runtime -d hello.jar
compile library: kotlinc hello.kt -d hello.jar
REPL: kotlin

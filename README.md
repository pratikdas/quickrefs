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
```shell
brew install kotlin
```
```shell
kotlinc -help
```
compile application:
```shell
kotlinc hello.kt -include-runtime -d hello.jar
```
compile library: 
```shell
kotlinc hello.kt -d hello.jar
```
REPL: 
```shell
kotlin
```
## Starting Flask
```shell
pip3 install Flask
```
```shell
flask --app hello run
```
```python
# hello.py

from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "Hello, World!"
```
## Virtual environments in python
python native way using venv
```shell
cd <new folder>
python3 -m venv .venv
source venv/bin/activate
```
```shell
pip3 install flask
```
```shell
deactivate
```
3rd paty: conda, virtualenv

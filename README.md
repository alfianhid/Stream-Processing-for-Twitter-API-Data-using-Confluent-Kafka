# Objectives
Make streaming processing using Kafka basic components that consume/subscribe data from the Twitter API. The twitter data used is up to students, feel free to explore.

# Requirements
1. Python 3
2. Docker
3. IDE (VSCode, Intellij, etc)
4. Terminal
5. Python libraries
```
pip install confluent-kafka
pip install tweepy
```
6. Twitter Developer account (https://developer.twitter.com/en/portal/petition/essential/basic-info)

# How to Run
1. Setup your Twitter Developer account to the Elevated level
2. Open your app project on Twitter Developer portal and copy the Bearer Token
3. Paste the Bearer Token to kafka_producer.py (line 23)
4. Change the "search term" to your choice (line 26)
5. Activate Docker, open terminal, and write
```
docker-compose build
docker-compose up
```
6. Open new terminal and write
```
python3 kafka_producer.py
```
7. Open new terminal and write
```
python3 kafka_consumer.py
```

# Objectives
Make streaming processing using Kafka basic components that consume/subscribe data from the Twitter API. The twitter data used is up to students, feel free to explore.

# Reguirements
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
4. Open terminal and write
```
python3 kafka_producer.py
```
5. Open new terminal and write
```
python3 kafka_consumer.py
```
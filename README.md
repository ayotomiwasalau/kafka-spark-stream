# Streaming app

STEDI has an application that collects data from seniors during a small exercise(opens in a new tab). The user logs in and then selects the customer they are working with. Then the user starts a timer and clicks a button with each step the senior takes. When the senior has reached 30 steps, their test is finished. The data transmitted enables the application to monitor seniors’ balance risk.

Read `./Guide.ipynb` and run the following files to test the application

```
./startup/startup.sh

./stedi-application/start.sh

./submit-event-kafkajoin.sh

./submit-event-kafkastreaming.sh

./submit-redis-kafka-streaming.sh

```
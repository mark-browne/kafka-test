
## consume messages:
```
docker exec --interactive --tty broker \
kafka-console-consumer --bootstrap-server broker:9092 \
                       --topic output-topic \
                       --from-beginning
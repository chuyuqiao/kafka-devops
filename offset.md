# offset
## EARLIEST_TIMESTAMP
bin/kafka-run-class.sh kafka.tools.GetOffsetShell --broker-list 127.0.01:9092 --topic test --time -1
## LATEST_TIMESTAMP
bin/kafka-run-class.sh kafka.tools.GetOffsetShell --broker-list 127.0.01:9092 --topic test --time -2

# QMH_template
This is a template in LabVIEW for the producer/consumer structure (QMH).
Uses User Event "stop" to close the Event Handling Loop (EHL) from the Message Handling Loop (MHL).
Uses a cluster to store local data in each consumer.
Gives an example of a multiple consumer structure, requiring a unique queue for each consumer controlled by the same producer.
Both templates contain a start and stop button that do nothing, but were used to test functionality.

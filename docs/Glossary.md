---
layout: default
title: Glossary
nav_order: 9
---
# Glossary

* **CONNECTOR_TYPE:** "Type of connector: Defines if the user wants to push the data to the connector or consume the data from the connector"
* **CONNECTORS:** "Different Connectors, where users want to push the data or to consume data from"
* **CONNECTION_NAME:** "Connection names of configurations saved for selected connector"
* **TRANSACTION_STATUS:** "Indicator of Transaction if it is running or not"
* **ACTIVEMQ_STATUS:** "Indicator of ActiveMQ Server if it is running or not"
* **START_TRANSACTION:** "Start the transaction"
* **STOP_BUTTON:** "Stop the transaction"
* **REFRESH:** "Refresh form-data"
* **DELETE:** "Delete transaction data from database and tag structure from tag browser"
* **SUBMIT:** "Save the config data"
* **RESET:** "Clear the form fields"
* **DATA_FORMAT:** "Data format to convert captured data to"
* **DATA_SEPARATOR:** "Separator between each message in a batch of data"
* **TRANSAFER_MESSAGE_SIZE:** "Size of the single batch"
* **TAGS_PER_MESSAGE:** "Number of messages to split into multiple batches". If the value received is 0, then all the tags will be sent in a single message
* **STORE_AND_FORWARD:** "If this box is checked, the unsent data will be stored in jms in case of connection loss"     
* **IS_SEQUENCIAL:** Checking this box ensures that when a connection is restored, the data stored earlier through “STORE_AND_FORWARD” is processed first before any new message is queued.                     
* **ACTIVEMQURL:** "URL of External ActiveMq Server"
* **DATA_PULL_INTERVAL:** "Interval of time between each message consumption"
* **TRIGGER_TYPE:** "Different data pushing ways"
* **DATA_PUSH_INTERVAL:** "How long to wait after pushing each batch of messages"
* **TAG_SCAN_TIMER:** "Scanning the tag values at this interval of time pushing the data"
* **ALL_TAG_TRIGGER:** "Whether to check all tags under the folder ProducerTags or just TriggerTags folder"
* **TRIGGER_RULES:** "Custom rules on tag value change, whether to push data on a particular value of tag"
* **OPERATOR_TYPE:** "Comparative operators to apply on tag value"
* **RULE_VALUE:** "Value of tag to be checked with a changed value of tag"



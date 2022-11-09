---
layout: default
title: Connectors
nav_order: 6
has_children: true
---
# Connectors

FactoCloudConnect supports the below mentioned connectors, before understanding each connector, some of the  important things in FactoCloudConnect.

## Tags
First we need to create a Tag Provider named as **FactoCloudConnect** in Tags section in Ignition Gateway. This will appear in Tag Browser in designer. When FactoCloudConnect module installed, it will create some nessasary tags under this **FactoCloudConnect** Tag Provider. 

**AMQConfigTags** - holds the ActiveMQ configuration details
**isTrialExpired** - checks the module license state, wheter running in trial mode or not.

When a new transaction is created a Tag folder is created in **FactoCloudConnect** tag provider with same name as transaction name. this tag folder holds another 4 types of tag folders in it. They are 

* **ConsumerTags** - keeps the consumed tags data 
* **ContorlTags**  - keeps the track for the messages sent and transaction status details
* **ProducerTags** - keeps the actual data tags for sending the data. 
* **TriggerTags**  - keeps the data tags for event based messaging based on trigger section in connectors.


## Config & Trigger
Each connector has tabbed section for **Config** and **Trigger**. 

### Config 
Config section allows below options

* **Data Format** - supported data formats by FactoCloudConnect are JSON, CSV, AVRO, SPARKPLUG-B.
* **Transfer Message Size** - allows to specify the transfer message size in KB, default is 5KB.
* **Tags Per Message** - allows to specify the no of tags per message to transfer.
* **Is Squential** - this option allows to process the data in sequential way.
* **Store and Forward** - this option allows to store the message and later forward the message to the desitination.
* **ActiveMQ Url** - allows to specify external ActiveMQ url to use
* **Enale Log** - this option allows to create the log of the messages.

### Trigger 
Trigger section allows below options

* **Trigger Type** - allows to send the messages are event based triggers, allowed trigger types are **Timer**, **OnTagChange**, **OnTagChangeAndTimer**, **OnTagValueChange**.

    * *Timer* event Transfers the messages on interval specified in *Data Push Interval* section.

    * *OnTagChange* event transfers the messages on any tag value changed in *Trigger Tags* folder, need to specify the **Tag Scan Timer** option

    * *OnTagChangeAndValue* event works like both *OnTagChange* and *Timer* based.

    * *OnTagValueChange* event transfers the message for selected tags from trigger tags and value condition based on those tags like *equals*, *not equals*, *greater*, *greater than equal*, *less*, and *less than equal*.


* **Data Push Interval** - allows to push the data at certain interval of time, allowed interval are **HOUR**, **MINUTE**, **SECOND**, **MILLIS**.

* **Tag Scan Timer** - allows to read the tag value on given interval, allowed interval are **HOUR**, **MINUTE**, **SECOND**, **MILLIS**.






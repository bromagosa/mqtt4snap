# MQTT4Snap!

MQTT4Snap! is a Snap! library for using [MQTT](https://en.wikipedia.org/wiki/MQTT) in Snap! and Snap4Arduino.

The default broker is  [test.mosquitto.org](https://test.mosquitto.org).

## Blocks and usage

Import &nbsp;&nbsp;&nbsp;   **[mqtt_standalone.xml](https://raw.githubusercontent.com/pixavier/mqtt4snap/master/mqtt-standalone.xml)**  &nbsp;&nbsp;&nbsp;  into Snap!.

Here you can see the blocks and a simple example to test:

![Minimal example](img/mqtt4snap.png)


### pub / sub blocks

**pub** and **sub** blocks are suitable for PubSub arquitecture based implementations.

![pub sub blocks](img/PubSub.png)

### request / response blocks

**request** and **response** blocks are suitable for asynchronous client-server architectural approach on a PubSub based infrastructure.

![request response blocks](img/PubSub_client-server_async.png)

### request reporter block

**request** block is suitable for synchronous client-server architectural approach on a PubSub based infrastructure.

![request reporter block](img/PubSub_client-server_sync.png)

### disconnect block

**disconnect** block accepts the value **all** as parameter, and then it closes all existing connections to MQTT brokers.


## Acknowledgents

Of course, this project wouldn't exist without:

- [MQTT.js](https://github.com/mqttjs/MQTT.js)
- The "fetch JavaScript" block from [Bernat Romagosa](https://github.com/bromagosa)


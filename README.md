# MQTT4Snap!

MQTT4Snap! is a Snap! library for using [MQTT](https://en.wikipedia.org/wiki/MQTT) in Snap! and Snap4Arduino.

The default broker is  [test.mosquitto.org](https://test.mosquitto.org).

## Blocks and usage

Import  **mqtt4snap_standalone.xml** into Snap!

Here you can see the blocks and a simple example to test:

![Minimal example](img/mqtt4snap.png)


### pub / sub blocks

Suitable for PubSub arquitecture based implementations

![pub sub blocks](img/PubSub.png)

### request / response

Suitable for asynchronous client-server architectural approach on a PubSub based infrastructure

![request response blocks](img/PubSub_client-server_async.png)

### request repoerter block

Suitable for synchronous client-server architectural approach on a PubSub based infrastructure

![request reporter block](img/PubSub_client-server_sync.png)

## Acknowledgents

Of course, this project wouldn't exist without:

- [MQTT.js](https://github.com/mqttjs/MQTT.js)
- The "fetch JavaScript" block from [Bernat Romagosa](https://github.com/bromagosa)


# ECHONETLite2MQTT

## How to set it up

MQTT parameters

| parameter           | description |
| `MQTT_BROKER`       | The MQTT broker's URL. starts with "mqtt://" or "mqtts://".  |
| `MQTT_PORT`         | The MQTT broker port number. (Default: 1883) |
| `MQTT_CLIENT_ID`    | The MQTT client id. (Default: empty)|
| `MQTT_USERNAME`     | The MQTT user name. (Default: empty)|
| `MQTT_PASSWORD`     | The MQTT password. (Default: empty)|
| `MQTT_OPTION_FILE`  | the MQTT option file path. The schema is [MQTT.js](https://github.com/mqttjs/MQTT.js) ClientOptions. (Default: empty)  |
| `MQTT_CA_FILE`      | The MQTT CA file path. If this file exists, it will be loaded and set as an "ca" option. (Default: not load)  |
| `MQTT_CERT_FILE`    | The MQTT cert file path. If this file exists, it will be loaded and set as an "cert" option. (Default: not load)  |
| `MQTT_KEY_FILE`     | The MQTT key file path. If this file exists, it will be loaded and set as an "key" option. (Default: not load)  |
| `MQTT_BASE_TOPIC`   | MQTT topic prefix. (Default:"echonetlite2mqtt/elapi/v2/devices") |

ECHONET Lite parameters

| parameter                               | description |
| `ECHONET_TARGET_NETWORK`                | Specify the network for ECHONET Lite in the format "000.000.000.000/00". (Default: Auto) |
| `ECHONET_DEVICE_IP_LIST`                | Specify the device IPs separated by commas. (Default: none) |
| `ECHONET_COMMAND_TIMEOUT`               | Specify the timeout for ECHONET Lite commands. (Unit: ms) (Default: 3000) |
| `ECHONET_DISABLE_AUTO_DEVICE_DISCOVERY` | Disable automatic device discovery. (default: off) |
| `ECHONET_ALIAS_FILE`                    | The file path for alias option file. (Defalt: (empty)) |
| `ECHONET_LEGACY_MULTI_NIC_MODE`         | Revert to legacy communication mode. (Default: off) |
| `ECHONET_UNKNOWN_AS_ERROR`              | Specifies whether to  treat unknown classes and unknown properties as errors. (Default: off) |

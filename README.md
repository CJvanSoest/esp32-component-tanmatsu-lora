# Tanmatsu LoRa component

This component implements a wrapper around the SX126X driver, presenting a consistent API for both remote and locally connected LoRa radios.

The local mode of this component will work on any ESP32 target. The remote mode is currently specifically implemented for Tanmatsu.

On Tanmatsu targets the ESP32-C6 radio running modified ESP-HOSTED-MCU firmware implements a LoRa interface via custom commands.

## License

The contents of this repository are made available under the terms of the MIT license, see [LICENSE](LICENSE) for the full license text.

## GPIO connections
# Circuit diagram
![SVG Circuit Diagram](./circuit.svg)
# Components
| Component name | Description |
| ---- | ---- |
| Raspberry Pi | Raspberry Pi with 40 pin J8 header |
| BMP280 | temperature and pressure sensor, uses I<sup>2</sup>C communication protocol, if needed can be changed to use SPI |
| OLED SSD1306 | small blue OLED display, 0.96" 128x64 pixels. Uses I<sup>2</sup>C communication protocol |
| DHT22 | temperature and humidity sensor, 1-wire communication protocol |
| IDC Adapter | 10 pin IDC / 8 pin JST / 4 goldpin adapter |
| PMSA003-C | particulate matter sensor (0.3 μm to 10 μm), software UART communication protocol using pigpio |
| R1-R4 | safety resistors in case GPIO are set to output |
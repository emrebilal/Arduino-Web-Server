# Arduino-Web-Server-using-AJAX
The Arduino web server hosts a web page (stored on the SD card) that displays DHT11 data. The values of the DHT11 sensor are updated (sending a request every second) on the web page using Ajax. An XML file containing the sensor values are sent from the Arduino to the web browser.
- The web page (index.htm) is stored on the micro SD card of the Arduino Wifi shield (or use Ethernet Shield).
- To access the Arduino web server, the IP address set in the Arduino sketch or automatically received is used.

Tutorial: https://startingelectronics.org/tutorials/arduino/ethernet-shield-web-server-tutorial/SD-card-AJAX-XML-web-server/

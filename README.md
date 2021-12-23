# OurWeather-to-HomeAssistant-NodeRed
 Ingest data to HomeAssistant from SwitchDoc Labs OurWeather v2.

 This is a Node-Red flow to ingest data from SwitchDoc Labs OurWeather via it's REST interface. 
 
 It's written specifically for the ESP32 verion of the WeatherPlus board. It may work on other versions, it may not.

 https://github.com/switchdoclabs/SDL_ESP32_OurWeather

https://shop.switchdoc.com/collections/weather/products/weatherplus-all-in-one-weather-station-controller

Installation:
- Import OurWeatherFlows.json into Node-Red on HomeAssistant. 
- Edit the Get-Weather-API node to reflect the IP or hostname of your OurWeather instance.
- Edit the Start node to adjust the polling interval to your needs.
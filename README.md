# ESP8266 HomeKit WeatherUnderGround PWS Weather Station

ESP8266 based  HomeKit Weather Underground PWS Weather Station using Bosch BME280 temperature, humidity, barometric pressure sensor, VEML6075 UV Index sensor, BH1750 light sensor and a Rain Gauge.

------
[![Instagram URL](https://img.shields.io/twitter/url/https/www.instagram.com/homekidd?label=Follow&logo=instagram&style=social)](https://www.instagram.com/homekidd) [![FaceBook URL](https://img.shields.io/twitter/url/https/www.facebook.com/HomeKiid?label=Like&logo=facebook&style=social)](https://www.facebook.com/HomeKiid) [![YouTube URL](https://img.shields.io/twitter/url/https/www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA?label=Follow&logo=youtube&style=social)](https://www.youtube.com/channel/UCkqC_6j1uyYVv7SO3jPe7KA)
------

[![GitHub All Releases](https://img.shields.io/github/downloads/HomeKidd/ESP8266-HomeKit-WeatherUnderGround-PWS/total?color=green)](https://github.com/HomeKidd/ESP8266-HomeKit-WeatherUnderGround-PWS/releases) 
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/HomeKidd/ESP8266-HomeKit-WeatherUnderGround-PWS?color=yellow&label=Latest%20Release)](https://github.com/HomeKidd/ESP8266-HomeKit-WeatherUnderGround-PWS/releases) 
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CEYEK69ZYG69S&source=url)
<br/>
<br/>


**For Usage and Configuration please read the [Wiki page](https://github.com/HomeKidd/ESP8266-HomeKit-WeatherUnderGround-PWS/wiki/)!**<br/><br/>

<a href="https://www.wunderground.com/dashboard/pws/IGYNGYS6"><img src="http://banners.wunderground.com/cgi-bin/banner/ban/wxBanner?bannertype=wxstnsticker_metric&weatherstationcount=IGYNGYS6" height="160" width="160" border="5" alt="Weather Underground PWS IGYNGYS6" /></a>

<a href="https://www.wunderground.com/dashboard/pws/IGYNGY1"><img src="http://banners.wunderground.com/cgi-bin/banner/ban/wxBanner?bannertype=wxstnsticker_metric&weatherstationcount=IGYNGYS1" height="160" width="160" border="5" alt="Weather Underground PWS IGYNGY1" /></a>


**Features:**

* Temperature
* Humidity
* Dew Point _(only when uploading to WunderGround)_
* UV Index _(only in 3rd party HomeKit apps!)_
* Daily and Hourly Rain in mm _(only in 3rd party HomeKit apps!)_
* Light intensity _(Lux and Watt/m2)_
* Leak Sensor (_aka Rain detection)_
* Barometric Pressure Measuring _(only in 3rd party HomeKit apps!)_
* Custom characteristic for detecting your altitude _(used for proper barometric calculation)_
* Custom characteristic for Temperature Sensor Offset _(only in 3rd party HomeKit apps!)_
* Upload data to [Weather Underground](https://www.wunderground.com)
* Reset button 
 

<br/>
<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Weather-Station-BME280/raw/master/images/homekifd_mockup_2.jpg" class="center" width="650"/>

<br/>

**Demo:**

<br/>
<img src="https://github.com/HomeKidd/ESP8266-HomeKit-Weather-Station-BME280/raw/master/images/faw.gif" class="center" width="250"/>

<br/>
<br/>

This project uses the Apple HomeKit accessory server library [ESP-HomeKit](https://github.com/maximkulkin/esp-homekit) from [@MaximKulkin](https://github.com/maximkulkin) for [ESP-OPEN-RTOS](https://github.com/SuperHouse/esp-open-rtos).<br/>

Although already forbidden by the sources and subsequent licensing, it is not allowed to use or distribute this software for a commercial purpose.<br/><br/>

<img src="https://freepngimg.com/thumb/apple_logo/25366-7-apple-logo-file.png" width="20"/> 

###### HomeKit Accessory Protocol (HAP) is Apple’s proprietary protocol that enables third-party accessories in the home (e.g., lights, thermostats and door locks) and Apple products to communicate with each other. HAP supports two transports, IP and Bluetooth LE. The information provided in the HomeKit Accessory Protocol Specification (Non-Commercial Version) describes how to implement HAP in an accessory that you create for non-commercial use and that will not be distributed or sold.

###### The HomeKit Accessory Protocol Specification (Non-Commercial Version) can be downloaded from the [HomeKit Apple Developer page.](https://developer.apple.com/homekit/)

###### Copyright © 2019 Apple Inc. All rights reserved.

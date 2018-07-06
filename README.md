# intellistar-emulator
A work in progress web application that displays weather information in the same visual presentation as the cable headend unit [Intellistar](https://en.wikipedia.org/wiki/IntelliStar).

## Overview
This is a local forecast segment that airs on The Weather Channel called the "Local on the 8s". The name is because it airs at timeslots that end in "8" (9:28, 2:48, etc.). The forecast is approximately a minute long and provides information on current and forecasted weather conditions. This type of forecast started in 1982 using WeatherStar units. It was later upgraded to Intellistar in 2003 and recieved various graphic changes over the years. This emulator uses the style that started in 2013.

## Looping
To get looping working properly, you may (as of Chrome M66) have to go to chrome://flags#autoplay-policy (Autoplay Policy) and change it to `User gesture is required for cross-origin iframes` or `No user gesture is required`  
To disable looping after it is enabled, click on the TWC logo in the info-bar in the top-left corner of the emulator.

## Instructions
1. Extract all contents into folder
2. Run index.html in Google Chrome
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

## Features
Most of core animation and logic has been replicated including severe weather alerts, forecast descriptions, crawl text, and the Doppler radar map.

## Background Blur
The background blur will not work by default. It is a feature that is disabled in chrome by default due to poor performance. To enable, go to chrome://flags and enable  *Experimental Web Platform features*.

## Screenshots
![Screenshot 1](/screenshots/1.png)

![Screenshot 2](/screenshots/2.png)

![Screenshot 3](/screenshots/3.png)

![Screenshot 4](/screenshots/4.png)

![Screenshot 5](/screenshots/5.png)

![Screenshot 6](/screenshots/6.png)

![Screenshot 7](/screenshots/7.png)

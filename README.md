<a href="https://youtu.be/7z8dJp4GOwY">
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/SocialDistance/socaildistancelogo.jpg" />
</a></br></br>
Hi friends, Back to office we will need a social distancing office badge, In this video we have made a device which helps to maintain the social distance, a little contribution towards the safety from COVID19. #socialdistance #arduinoproject</br></br>

<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/SocialDistance/Circuit%20diagram.jpg" /></br>
Which you will need following parts:</br></br>
Arduino NANO, https://amzn.to/3hB8Pwf</br>
HC-SR501, https://amzn.to/3aJAOHX</br>
HC-SR04, https://amzn.to/2zLomJU</br>
12 bit WS2812 5050 RGB Round LED</br>
Buzzer, https://amzn.to/2BeYzu3</br>
Jumper wires, https://amzn.to/3jCHhZd</br>

Note</br>
In this project I used the HC-SR501 human body infrared sensor module. The HC-SR501 human body infrared sensor module has two triggering methods. One is non-repeatable triggering: that is, after the sensor outputs a high level, the delay time is over，The output will automatically change from high level to low level. To put it simply, it will output a high level when it senses human movement, but after the time of its delay adjustment button is over, it will not continue to sense even if a person moves in front of it. HC-SR501 has a lockout time of 0.2 seconds, during which time it will not work. It will continue to sense after the lockout time is over. There is also a repeatable trigger mode: after the sensor outputs a high level, during the delay period, if a human body is moving within its sensing range, its output will remain high until the person leaves. Change the high level to low level (the sensing module will automatically extend a delay time period after detecting every activity of the human body, and take the time of the last activity as the starting point of the delay time). Simply put, if you keep moving in front of the human infrared sensor module, the HC-SR501 will always output a high level.
<img src="http://dkardu.oss-cn-hongkong.aliyuncs.com/SocialDistance/Circuit%20diagram.jpg" /></br>

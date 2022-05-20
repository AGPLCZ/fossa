![FOSSA](https://user-images.githubusercontent.com/33088785/169420554-1b5a132a-3235-44ac-9ede-35d7c592e6e7.png)

## OFFLINE, FOSS, CHEAP, BILLS/COINS, EASY CONFIG WEB PORTAL 


> <i>Join our <a href="https://t.me/makerbits">telegram support/chat</a>.</i>

## Video tutorial

(coming soon)

## Parts (PROJECT COST UNDER £200!)
* RPI_ILI9486 3.5 inch TFT (the type the Raspiblitz uses) **£15**
* ESP32 NodeMCU 32s **£3**
* Generic USB cable, with data (used to make the Bill Acceptor config cable) **£2**
* Breadboard (some bread boards are two small for esp32 and two are required) **£5**
* DG600F(S) Multi Coin Acceptor **£30**
* NV10USB+ bill acceptor (Seems to be plenty 2nd hand ones on ebay) **£70**
* Storage box (the readily available "aluminum medicine box" boxes on amazon are perfect) **£30**
* Screw Terminal block **£1**
* 12v power supply (12v battery also works well, for unplugged version) **£8**
* 12v to 5v step down converter **£5**
* Male/female, female/female, male/male GPIO jumpers **£5**

![fossaparts](https://user-images.githubusercontent.com/33088785/169537001-983c7e17-1163-4f13-9ac7-c695e0e7277f.jpeg)

## Screen wiring

![image](https://user-images.githubusercontent.com/33088785/169515768-183ccd70-8f3b-4334-a4f0-9ccccdbcbf93.png)

## Coin acceptor wiring

![image](https://user-images.githubusercontent.com/33088785/169517488-65bfba37-0c9c-4dc4-9533-c6c4517cc1ff.png)

## Bill acceptor wiring

![image](https://user-images.githubusercontent.com/33088785/169518370-2bdf7acd-e5f9-4d34-bd34-26854b805704.png)

## Relay wiring

![image](https://user-images.githubusercontent.com/33088785/169520286-a6c9c1bc-627b-494c-a9da-d752c15e56c6.png)

## Button wiring

![image](https://user-images.githubusercontent.com/33088785/169520797-d7256bb8-8b4c-48c6-b480-11918d3df497.png)

## Installing arduino + libraries

Install the Arduino IDE,<br>
https://www.arduino.cc/en/Main/Software

Install the ESP32 hardware,<br>
https://github.com/espressif/arduino-esp32#installation-instructions

Copy the libraries from this projects <a href="/libraries">libraries</a> folder, to your `"/Arduino/libraries"` folder (usually in OS `"Home"` directory)

![BITCOIN](https://i.imgur.com/mCfnhZN.png)

## Compiling/uploading

* Connect your ESP32 and hit upload. 
* Tap the reset button on the ESP32 when Arduino has finished compiling and you get the little dots `...---...---` in monitor.

## Configuring

* Go to your LNbits install (you can use our demo server for testing).
* Enable LNURLDevices extension.
* Create an ATM attached to wallet, select a currency and set percentage profit
* Copy the LNURLATM string

![image](https://user-images.githubusercontent.com/33088785/169524860-203a6c07-eb61-4b68-b493-098ca6333c01.png)

Hit button on ATM boot (when you see the logo screen to trigger access point).

* Connect to the portal over you phone (default password: `ToTheMoon`).
* Enter your credentials
* Reboot ATM
* Profit

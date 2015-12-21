# BitRobot
Arduino &amp; Bitcoin for the masses

# Howto

You'll need the [aJson arduino library](https://github.com/interactive-matter/aJson)

Upload _firmware/arduinoFirmware/bitcoinMachine_ to the arduino, see the pins I use in the code.


Next you'll need node.js and some modules:

```
//install modules using npm
cd server
npm install ws
npm install serialport
npm install json-scrape
npm install moment	

//run the server that listens to the blockchain and tells the arduino what to do
node BitRobot.js 
```

# Bitcoin donation

If you like it please consider sending me some bitcoin this encourages me to build and share more. I'm also open to collaboration, so you can email me on [rouan@8bo.org](mailto:rouan@8bo.org)

![alt tag](https://raw.githubusercontent.com/fluentart/BitRobot/master/bitcoinDonation.png)
<strong>1EZ6S8YqfxzfMKCCtpzKeEJW1qMthQnCuD</strong>


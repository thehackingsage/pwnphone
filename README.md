# PWN PHONE - DREAM DEVICE FOR HACKERS

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone.gif?raw=true" /></p>

The Pwn Phone is a real-life product made by a Boston-based startup called Pwnie Express. The "dream device for hackers" allows users to check if there are any vulnerabilities in wired, wireless, or Bluetooth networks, and it looks like a regular cell phone. If you have a spare $1,095 sitting around, you can buy one here.

Pwn Phone 2014 Demo : [YouTube](https://www.youtube.com/watch?v=He_bxvcvFGE)

but if you have few things then you can also build your own Pwn Phone.

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_1.jpg?raw=true" /></p>

## Things You Need :

● Nexus 5 : [Search Online](https://www.google.com/search?q=BUY+GOOGLE+NEXUS+5)

● A Linux-based system (i'm using Kali Linux)

● Pwn Phone's Rom

● WiFi and Bluetooth Adaptor that support packet injection (for wireless pentesting)

● OTG Cable

## How To Flash Rom :

Note : this process will erase your all data from your phone so create backup before flashing the rom.

● Here I'm using Linux system, so open your terminal as root user

● Update : `apt-get update`

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_2.jpg?raw=true" /></p>

● Install ADB & Fastboot : `apt-get install android-tools-adb android-tools-fastboot`

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_3.jpg?raw=true" /></p>

● Unzip the Pwn Phone's Rom

● make flash.sh file executable : `chmod +x flash.sh`

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_4.jpg?raw=true" /></p>

● Turn off your Nexus 5 and reboot it into fastboot mode Holding Power + Vol. Down Key and Connect it with you PC using USB cable

● then Unlock Bootloader of Your Nexus 5 : `fastboot oem unlock`

● Open Terminal and flash rom : `./flash.sh`

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_5.jpg?raw=true" /></p>
<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_6.jpg?raw=true" /></p>
<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_7.jpg?raw=true" /></p>

## Download Links :

● Download PwnPhone ROM (Nexus 5) : [Google Drive](#) | [MEGA](#)

## Video

YouTube : [How to turn your phone into a "Pwn Phone"](https://www.youtube.com/watch?v=x-TLSKqg6CI) (Language : Hindi)

## License :

[MIT Licence](https://github.com/thehackingsage/hacktronian/blob/master/LICENSE)

That's It... If You Like This Repo. Please Share This With Your Friends..

& Don't Forget To Follow Me At [Twitter](https://www.twitter.com/thehackingsage), [Instagram](https://www.instagram.com/thehackingsage), [Github](https://www.github.com/thehackingsage) & SUBSCRIBE My [YouTube](https://www.youtube.com/channel/UCYK1n9A4TUq1CvGc6F3DzoA) Channel..!!!

***Happy Hacking!!!***
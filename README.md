# PWN PHONE - DREAM DEVICE FOR HACKERS

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone.gif?raw=true" /></p>

The Pwn Phone is a real-life product made by a Boston-based startup called Pwnie Express. The "dream device for hackers" allows users to check if there are any vulnerabilities in wired, wireless, or Bluetooth networks, and it looks like a regular cell phone. If you have a spare $1,095 sitting around, you can buy one here.

Pwn Phone 2014 Demo : [YouTube](https://www.youtube.com/watch?v=He_bxvcvFGE)

but if you have few things then you can also build your own Pwn Phone.

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_1.jpg?raw=true" /></p>

## Things You Need :

● Nexus 5 : [Search Online](https://www.google.com/search?q=BUY+GOOGLE+NEXUS+5)

● A Linux-based system (i'm using Kali Linux)

● Pwn Phone's Rom : [Nexus 5](https://drive.google.com/open?id=1FH7QOZwE6H9lgyUAKixtPvd9WKqImE9w)

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

● Choose your device and the installation process will begin.

<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_6.jpg?raw=true" /></p>
<p align="center"><img src="https://github.com/thehackingsage/pwnphone/blob/master/img/pwnphone_7.jpg?raw=true" /></p>

● Once the installation process completed your device will automatically rebooted and ready to use.

## My Opinion :

I know because of Mr.Robot's popularity many people would like to try it.. but currently i think the developers of Pwn Phone stoped working on this project because there is no update or latest version available of the previous pwn phone rom, even the old rom is now not available in their official website.. In past few months many people requested me to upload the pwn phone's rom that's why i'm updating this repository now..

i recommend you guys to try [Kali Nethunter](https://www.kali.org/kali-linux-nethunter/). it is also free and much better than pwn phone and most important thing, you will receive the regular updates..

Watch This : [Kali Nethunter - Everything You Need To Know + Installation](https://www.youtube.com/watch?v=7QKqHWosCsU) (Language : Hindi)

## Download Links :

Download PwnPhone ROM for Nexus 5 : [Google Drive](https://drive.google.com/open?id=1FH7QOZwE6H9lgyUAKixtPvd9WKqImE9w)

## Video

YouTube : [How to turn your phone into a "Pwn Phone"](https://www.youtube.com/watch?v=x-TLSKqg6CI) (Language : Hindi)

That's It... If You Like This Repo. Please Share This With Your Friends..

& Don't Forget To Follow Me At [Twitter](https://www.twitter.com/thehackingsage), [Instagram](https://www.instagram.com/thehackingsage), [Github](https://www.github.com/thehackingsage) & SUBSCRIBE My [YouTube](https://www.youtube.com/channel/UCYK1n9A4TUq1CvGc6F3DzoA) Channel..!!!

***Happy Hacking!!!***

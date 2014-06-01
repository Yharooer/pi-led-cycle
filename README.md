Pi-LED-Cycle
============

A program which tests Charlieplexing on the Raspberry Pi with 4 Pins. It cycles through each of the 12 pins at a configurable speed. It is the testing program to make sure everything is wired correctly for my <a href="https://github.com/Yharooer/Pi-LED-Clock.git">PiClock project</a>.
  
## Setup ##
There should be two circuits which look like this:  
<img xlink:href="http://bentleycarr.com/res_local/tech/clock_charlieplexing.svg" src="http://bentleycarr.com/res_local/tech/clock_charlieplexing.svg" />  
where each of the four parts at the bottom correspond to `GPIO0`-`GPIO7` on the following diagram:
<img src="http://pi4j.com/images/p1header.png" />  
Image from <a href="http://pi4j.com/usage#Pin_Numbering">pi4j.com</a>.  
  
Then execute:

    wget https://pi4j.googlecode.com/files/pi4j-1.0-SNAPSHOT.deb
    sudo dpkg -i pi4j-1.0-SNAPSHOT.deb
    wget https://github.com/Yharooer/Pi-LED-Test/blob/master/bin/PiLEDTest.jar
  

More info at <a href="http://bentleycarr.com/tech/ledclock.html">bentleycarr.com</a>.
## Usage ##
    java -jar PiLEDTest.jar


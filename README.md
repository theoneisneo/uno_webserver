# How to set arduino uno wifi  

1.
connect uno wifi to mac/pc via usb
or any way that can power on uno

2.
find wifi SSID "Arduino-Uno-WiFi-XXXX" and connect with mac/pc (should be no password)  
if can not connect, try press "RESET" on uno

3.
visit  
http://192.168.240.1/  
with mac/pc
this is uno setting page

4.
see left side  
"settings" -> "WIFI"  
choose wifi that uno should connect, like "StatsDontLieButI"
then get a new ip address which uno has (could via DHCP or Static IP)

5.
see right side  
switch WiFi mode to STA (not AP+STA)

6.
modify arduino hostname if you want

7.
change mac/pc wifi back to which uno connected ("StatsDontLieButI") and visit  
http://<uno_local_ip>/home.html  
or  
http://<arduino_hostname>.local/  
default is  
http://arduino.local/  
this is uno setting page  

8.
open Arduino IDE and try  
"Tools" -> "Board" / "Port" then "Get Board Info"  
to see the connection is success or not

9.
upload code and visit  
http://<uno_local_ip>/arduino/webserver  
or  
http://<arduino_hostname>.local//arduino/webserver  
to see the webserver result  

http://arduino.local/console.html  
is also a choice, could see WiFi console here  


ref:  
http://www.arduino.org/learning/getting-started/getting-started-with-arduino-uno-wifi  
http://labs.arduino.org/WebServer

# How-can-we-control-a-device-and-make-an-alarm-with-the-node-red-dashboard.
Here, I try to show how to generate random data in two ways for two types of temperature. One is by the node which is called a random node and another one is the function node. We have to write code in JavaScript.
And I make a function that when I select the manual mode that time the active and inactive button will work. But when I select schedule mode that time the button means the active and inactive buttons will not work. 
In the meantime, I use a colour function node when I select manual and change the button, it will also change the colour status. We can easily find out what is going on in the system.


<img src= "Node-red Chiller_Machine control flow.png" width=800>

<img src= "Chiller_Machine control by dashboard.png" width=800> 

 
I also create an alarm dashboard where I tried to show the real status of the device.


![](Alarm.png)

Here is the alarm node-red flow.

<img src= "Node-red flow for Alarm.png" width=800> 


Like, if the temperature range is below 50 then it will show normal mode and the colour will be lime. If the temperature range from 50 to 70, that time it will show major and colour will be yellow. But the temperature range more than 70 and below 100 then it will show red. 
Final looks of the dashboard where I tried to show current dates and times also.

<img src= "Final dashboard.png" width=1000> 

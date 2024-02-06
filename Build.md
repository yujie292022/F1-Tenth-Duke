# F1-Tenth-Duke
## Start of Journy
  We extend our gratitude to Professor Zavlanos for generously providing us with the F1 Tenth prototype he crafted in 2020. This valuable machine came into our possession through the kind support of Professor Delagrammatikas in September 2023, marking the inception of Duke University's inaugural F1 Tenth team.
![The First Look of Our Car](Images/First%20Look.jpg)
Since we didn't build the car from sketch, if you start from sketch, please read [F1 Tenth Official website](https://f1tenth.org/build.html#)

## Initial Condition
  However, the car was not in a runnable condition.   
        1.Powerboard only has 1 output  
        2.TX2 USB ports didn't work  
        3.TX2 was using Ubuntu 18.04 and using unknown password  
        4.Missing connector and adaptor for battery  
  We write this down to remind future project users if anything anything doesn't work exclude these, it could be something we didn't find out.

## Final Structure
  All material except something like bolts should be able to find in our [BOM](/BOM/Master%20BOM.xlsx) 

  Due to the limit budget, we only replace those neccesary components with certain reason  
        1. Changed TX2 to NX. Since Ubuntu 18.04 is too old for our laptop and we didn't find the way to fix the usb port, we decided to buy a Jetson Xavier NX8. And we add a 256GB SSD and wifi module by ourselves.  
        2. Rebuild 3 powerboards  
        3. Add adaptor and connector for battery.  

  The ESC is FSESC which is using VESC 6 architecture instead of VESC. This is what we got from Prof. Zavlanos and it works.

  Here is a picture to show the main component of our car.
  ![The First Look of Our Car](Images/Overview.jpg)

And here is the final looks when it is running.
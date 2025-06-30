# Lerobot Software

Up until this point, I have worked on assembling the leader arm and follower arm. FRom now on I will be focusing on the software for the arms. I will be following the guide for the Koch v1.1 arms from hugging face. 
<br><br>

### Initial setup

### Start up
There is a procces you must follow each time you want to work with the arms. You must connect them to power, making sure to connect the 12v power supply to the follwer arm and the 5v power supply to the leader arm. the follower arm needs 12vs for the two xl 430 motors near its base. The rest are xl330 motors so the power must pass through a voltage reducer before getting to the xl330 motors. Once they are connected to their 
respective power supplies you can connect them via usb to your computer.  

Once you have everything connected you need to bind the usb ports you are using. Go into powershell and run it as an administrator. You need to see which ports you have to bind so run
```
usbipd list
```
This will list all the usb devices currently connected to your computer, it should look somthing like this.

![image](https://github.com/user-attachments/assets/09e1785a-d50e-4de0-a4cb-c6a3cc20ff42)


<br>

### Calibration

### Teleoperation 

### Data collection

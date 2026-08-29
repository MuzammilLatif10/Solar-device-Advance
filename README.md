# Solar Device Advance

An ESP32-based DIY solar/UPS controller designed to add solar management, power monitoring, automatic source switching, and configurable control functions to a Car Inverter Or conventional UPS.

 <img width="940" height="625" alt="image" src="https://github.com/user-attachments/assets/f5884ced-a75b-4995-9580-a0315935c76d" />


⚠️ Safety Warning: This project can involve battery currents, inverter output, and potentially lethal AC mains voltage. Do not work on energized circuits. Use appropriate fuses, isolation, protection, wiring, relay ratings, and enclosure clearances.

 
# Video link：

Will be uploaded soon.

# Project Support & Sponsors

The development of Solar Device Advance was made possible with support from OSHWLab, EasyEDA, and JLCPCB.
We sincerely thank these organizations for providing complimentary PCBs and electronic components used during the development and testing of this project.

OSHWLab    
EasyEDA     
JLCPCB

Thank you to OSHWLab, EasyEDA, and JLCPCB for supporting DIY and open-source hardware development.


# Introduction

This Solar Device enables the user to built your own Solar System using a car inverter & charge controller OR to convert conventional UPS into Solar inverter.
Existing small/household UPS units provide battery-backed AC output but typically do not accept solar input or intelligently prioritise solar energy. Retrofitting these UPS units with a dedicated controller converts them to hybrid solar inverters at a fraction of the cost of buying a commercial solar inverter.

Parameter	        Description     
Controller	       ESP32     
Display	          1.8" TFT       
Current sensing	  ACS712        
Power sources	    Solar / Grid / Battery        
Inverter	         Conventional UPS / Car inverter       
Solar charging	   External charge controller        
Source switching	 Relay-based           
User interface	   TFT + keypad             
Connectivity	     Wi-Fi / Bluetooth           
Firmware	         ESP32            
Project type	     DIY / Open Source         

# Project function    
The controller integrates power monitoring, Solar charge regulation, automatic transfer switching (between grid, battery, and solar). It monitors PV voltage, battery voltage,  Output/load current, and grid status; then makes intelligent switching.

<img width="1004" height="747" alt="image" src="https://github.com/user-attachments/assets/51fdfb3b-a4a5-411b-8e9d-3abb3be39c90" />

 # User Interface
The Device provides a menu-based interface for system monitoring and configuration.

<img width="759" height="536" alt="image" src="https://github.com/user-attachments/assets/b73aef94-2dbc-4d85-bdc5-7f43401628cd" />

1.	Working mode: Running on Grid or Battery   
2.	Solar Status  
3.	Load Status  
4.	Grid Status  
5.	Battery Status  
6.	Settings  

# Hardware description
## 1.	Main Board
<img width="465" height="571" alt="image" src="https://github.com/user-attachments/assets/ece9ef79-3af2-4063-88e8-50e893d65542" />

    <img width="455" height="552" alt="image" src="https://github.com/user-attachments/assets/eff732cf-c847-46b2-8864-910d977a6de4" />
    

###  MicroController
The main controller is based on an ESP32.   
The ESP32 handles:  
•	System-state monitoring  
•	Relay control  
•	Display control  
•	Keypad input   
•	Settings   
•	Fault handling   
•	Operating logic  
•	Communication functions  
The ESP32 also provides Wi-Fi and Bluetooth/BLE hardware for possible future expansion and remote monitoring functions.  



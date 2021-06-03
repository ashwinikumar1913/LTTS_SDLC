# Requirements 🎯

## ▶️ Introduction 💬
It has been a challenge from long time for an electronic voting system that proves to satisfy all the legal requirements of voting. Decentralised technologies has been compelling technological advancement in the information technology world. Blockchain technologies is based on distributed ledger system and offers innumerable applications with features like immutibility etc., benefiting sharing economies. This paper focuses to asses the use of blockchain as a service to implement electronic voting systems. The paper identifies the limitations,both technological and legal, of the current voting system and briefs how realizing such system with using blockchain can be benificial. Through the description of proposed architecture, the process of an election and implementing a blockchain-based system the paper explains how the security is improved and how the limitations can be overcome.

## ▶️ Research 📖
In Todays world of internet almost every device is conneted to internet hence traditional fields of embedded system, wireless sensor networks, control system, automation systems are together interconnected to form the IoT and also all the devices connected helps to make human life easier.

## ▶️ Specific Requirements 💼
### ↪️ *External Interface Requirements*
* The user should be simple and easy to understand and use. Also be an  interactive interface .The system should prompt for the user and administrator to  login to the application and for proper input criteria 

  ### ✅ *User Interface* 👨‍🦱
  * The UserInterface should be user friendly for the user to interact with.
  * It includes basic login and registration through which user can enter and control the system
  * controll system UI are very well designed so that user can get great experiance
  * FAQ section being introduced for intraction of user with admin and others

  ### ✅ *Hardware requirement ⛓️* 
  * Raspberry pi- The central Processing and controlling part of this system use to send data from sensor to database, control GPIO pin of relay board.
  * 5 Port Relay board 
  * 5 V 2 Ampere Dc adapter 
  * Voltage Regulator- A voltage regulator is being designed to operate 240 Volt power supply from digital circuit.
  * Bulbs – For demonstration purposes we have used 100-watt bulb
  * Fan – For demonstration purpose to show intensity control of fan speed.
  * Wires – For making internal and external supply of power
 
  
  ### ✅ *Software requirement 🖥️*
  * Google firebase (As a database)- As to make our system Realtime and keep record of states firebase database is used. It also triggers the notification  
  * Nodejs as a server – This server is running on raspberrypi for continuous monitoring of states from all appliances and keep it up to date on firebase database.  
  * GPIO – A digital pins which gives 0,1 states to control the relay and the sensors.
  * Json - for front-end as well as backend
  * JS, HTML, CSS, bootstrap – Tools for designing of web application for home automation.

### ↪️ *Functional requirements 🗃️*
* User can on/off the fan and light depending on requirement. 
* FireBase Is used as a controll center as realtime database. 
*	Login as well as registration is required for using controll center. .  

### ↪️ *Description :
* It basically includes two section 
  ### ✅ *Product Perspective*
  * Through web technology and for controlling and monitoring. User can control- switch on/off the lights and fans in the room.
  * User can operate through dashboard switch and also monitor using website by a distance.
   
  ### ✅ *Product Features:
  * Status of equipment’s in the House can be checked and monitor through web application.
  * Remotely controlled on the System. 
  * fast response of website and mobile app for seamless use. 
  * Easy to install and set-up.

## ▶️ Cost and Features :
### ↪️ *Cost*
All the hardware as well as software cost sum around 9k indian rupee

### ↪️ *Features*
  * Controlling home appliances via mobile or web interface for labor-saving.
  * Security alert to detect intrusion, gas leakage and fire.
  * IoT based door locking system (future integration).
  * Efficient energy conservation.
  * 
### ↪️ *Software Model*
* Waterfall model was opted to make this project.
* It Made easy to first gather all the resources and plans required for this project.
* Then carrying out the proposed model in respective order.
* And finally implementing the software with testing and maintenance made it successfully


## ▶️ Defining the System
### Raspberry pi
### Setup raspberry pi for use:
    1	Install the Raspbian os to raspberry pi
    2	Enable the ssh client and vnc viewer or remote access
    3	Install the pyrebase for streaming of data to database
    4	Install the Django for running python scripts 
    5	Configure the ports and run the python scripts programmed to control GPIO and sensors

 ### Relay Module:
    1.	Connect the ground and vin pin of relay to respective raspberry pi board for power
    2.	Connect the relay pin 1,2,3,4,5 to 5, 9,13,17,21 GPIO pins of raspberry pi board
    3.	Connect all the appliances to relay 240Volt slot for use


### Database
* MongoDB used for storing credentials.
* Firebase for realtime interaction.
    
## ▶️ SWOT ANALYSIS
![SWOT-Analysis](https://github.com/ashwinikumar1913/LTTS_SDLC/blob/main/1_Requirement/SWOT-ANALYSIS.png)

# ▶️ 4W&#39;s and 1&#39;H

## ↪️ Who:

This tool is a helping hand for Home as well as office user.

## ↪️ What:

It generally helps in controlling home appliance remotely.

## ↪️ When:

When user is outside of his/her home or office he/she can controll appliance remotely. 

## ↪️ Where:

Can be used at places like smart building ,healthcare as well as in smart home. 

## ↪️ How:

User can interact with controller after registration and login. Through controller user can control fan and light and swithting it on or off accoring to requirement

# Team4_RFID BASED ENTERTAINMENT PAYMENT 
GROUP MEMBERS
HABUMUGISHA Fulgence 218015284
GASANA James Madson  220014138
INEZA Yves   
UWANTEGE Stela prossy
MUNYANEZA M Adolphe 

ABSTRACT
 RFID BASED ENTERTAINMENT PAYMENT System is a new an approach in public entertainment system useful for more efficient, accurate, time saving, leakage reduction, increase of productivity and cashless. The conventional system of buying tickets for a certain event which is manually has drawbacks like inaccurate quantity of places, time consuming, and Ticket theft.
 In this project, we proposed RFID based Entertainment Payment System technology instead of the conventional system. To buy the ticket you need to show the registered RFID tag (it should be registered by company that sells ticket) with amount   equivalent   to the ticket he/she want to buy then you will swipe your RFID tag to  the RFID reader(hold by ticket wholesalers), then controller check the customer codes and details of amounts in the card. After verification then customer need to enter the required number depending to the sit of his/her choice   by using keypad then microcontroller (system) send the message with deducted amount, balance on the account, sit number and category on the through GSM technology.

OBJECTIVE

In this project, the proposed concept is to replace the manual work in public entertainment payment system .RFID based Entertainment Payment System is automated by using ATMEGA2560. Conventional/manually system is replaced by smartcard in which  all the details about users are provided in it. In our system, we proposed connecting the system at ticket wholesaler. Hence it is possible to prevent the corruption and irregularities during buying tickets for a certain event like big concert or at the stadium during football game. 
The conventional/manually system is not trustworthy   and not meeting the requirements of the users where you can buy ticket and your place is not guaranteed or they sell tickets greater than the available sits.

Our system will solve the problem of crowd of people  paying cash since in our system it is to swipe card and system deduct money and give you the sit number immediately without delay, our  system also is cashless and no printout so it is environmental friendly. 
In our project we designed the hardware based on case study of stadium with three (3) different site (regular, VIP and VVIP), the user has to enter the required sit type on keypad and then swipe the rfid tag to the rfid reader then LCD will display the sit type, sit number, amount deducted and balance and if no enough money the system will show the balance and message that no enough amount and suggest for recharge the card. All these actions are controlled by the Arduino mega 2560 microcontroller. GSM module is included in our system to send data (sit type, sit number, balance to the customer).

REQUIREMENTS
Hardware requirements
Our project requires different components for implementation as listed below with role of each in our project
1.Microcontroller (Arduino mega 2560)
2.RFID (Radio frequency Identification) tag
3.RFID Reader
4.GSM Module (SIM 900)
5.Keypad
6.LCD 
7.Accessories like breadboard, jump wires

1.Microcontroller( Arduino mega 2560)
The Arduino MEGA 2560 is designed for projects that require more I/O lines, more sketch memory and more RAM. With 54 digital I/O pins, 16 analog inputs and a larger space for your sketch it is the recommended board for 3D printers and robotics projects. Microcontroller (Arduino mega 2560).the role Arduino in our project is to process the code.

![Capture](https://user-images.githubusercontent.com/61348839/75912415-da8d1200-5e59-11ea-8efb-db9ef4ad8e3e.PNG)


2.RFID(Radio frequency Identification) tag
Radio-frequency identification (RFID) uses electromagnetic fields to automatically identify and track tags attached to objects. An RFID tag consists of a tiny radio transponder; a radio receiver and transmitter, RFID tag is used to keep data concerned with customers like   amount (money)   and should be registered in the system.

![1](https://user-images.githubusercontent.com/61348839/75913092-f7761500-5e5a-11ea-9fd0-d8432962526c.PNG)


3.RFID Reader
A RFID Reader is a device that uses radio-frequency waves to wirelessly transfer data between itself and a RFID tag/label in order to identify, categorize and track assets. It will be  used to read data on the tag.

......................................

4.GSM module (SIM 900).
The SIM900 is a complete Quad-band GSM/GPRS solution in a SMT module which can be embedded in the customer applications. Featuring an industry-standard interface, the SIM900 delivers GSM/GPRS 850/900/1800/1900MHz performance for voice, SMS, Data, and Fax in a small form factor and with low power consumption. GSM module (SIM 900).This is used send sms to the customer when you swipe your Rfid tag to the Rfid reader.

![22](https://user-images.githubusercontent.com/61348839/75913439-9e5ab100-5e5b-11ea-8a07-46c85ccfc62f.PNG)

5.Keypad
 Keypad. This is used to enter data in the microcontroller

![11](https://user-images.githubusercontent.com/61348839/75913914-7d469000-5e5c-11ea-9314-411ff2d53300.PNG)


6.) LCD.
This is used to display sms with available sit type, sit numbers, available places.

![ww](https://user-images.githubusercontent.com/61348839/75914498-897f1d00-5e5d-11ea-8cca-51c0721bd4c6.PNG)
SOFTWARE REQUIREMENTS
Arduino IDE

METHODOLOGY
1.Observation
The observation is done in more than 10 night clubs, 8 football stadium and 4 volleyball matches and we observed that both attendants and service deliver suffer when it comes to payments (tickets collection and tickets selling). Current payments are not automated, it requires to pay cash bay hands (manually) then get a receipt, this lead to wasting time, wrong calculations, inaccurate service and insecurity. Designing a system to avoid the manual work in public entertainment spaces would solve the mentioned issues.
2.Interview
Interview is the research method done in order to know how public entertainment space attendants can use an efficient payment method. During this method, it was asking classmates, media experts, football and volleyball fans, television viewers and others especially those who use those space on what they think about the current payment method. This Interview was very helpful, because while interviewing people, you can even see the way they feel.

IMPLEMENTATION OF THE PROJECT 

.................................


THE WORKING PRINCIPLE OF THE SYSTEM
The main part of our system is based on the RFID and GSM technology. RFID stands for Radio-Frequency Identifications. The RFID is small electronic device that consist of a small chip and an antenna. The chip typically is capable of carrying 2,000 bytes of data or less. Customer needs to enter sit type through keypad connected to to Rfid reader and the available places are shown then swipes the Rfid tag to pay the chosen sit and then the money will be deducted from the card and receive the sms with sit number in chosen sit type and it will be displayed on LCD. Since the controller has the code inside it will recognize the data coming from RFID by comparing it with the database. Once the user is identified (if registered), it will know if the card is not registered no action will take place.

CIRCUIT DIAGRAM OF THE SYSTEM
...................................



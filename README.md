# Innovaccer-summer-intern
# Prerequisite

All the python script that have been created are tested on python and Django . The mail is being sent using 



### Why Twilio

Twilio is an open source cloud communications platform as a service which allows software developers programmatically to make and receive phone calls, send and receive text messages, and perform other communication functions using its web service APIs. Twilio uses Amazon Web Services to host telephony infrastructure and provide connectivity between HTTP and the public switched telephone network (PSTN) through its APIs. Twilio uses a simple syntax written in many web languages. It is completely agentless. 

### Why SMTP

The Simple Mail Transfer Protocol (SMTP) is a communication protocol for electronic mail transmission. SMTP is the Internet standard for sending and receiving emails. Email clients use SMTP to send messages to a mail server for delivery while email servers use it to forward messages to their recipients. 


## How to Run

How to Run
The app is to be run on local virtual environment as python version 3.6 is been used .
Then you'll have to update the email host user and password in settings.py –
 
And finally, update the twilio SID and token in settings.py so that sms function works properly -
 


About the app
The app supports following features

•	Different Signup and Login for Users and Host, to prevent ghosting

•	Personalized Dashboard for Users and Hosts

•	Users Dashboard show’s hosts available to them 
•	Hosts Dashboard shows the users which have visited them

•	Email and SMSs feature on check-in and check-out



# Application Flow
## Application checks if user already logged in or not

o	For existing user his name is already there on host list 
o	Just select the name of host in drop box menu
o	Otherwise, direct to Page
## To add a host

o	Access Add Host section by clicking on Floating Action Button (Host) on Page
o	Fill in valid details
o	Click on Submit Button and the host will be added.
## To Check-In

o	Access Check In section on Page Fill in valid details
o	Click on Submit Button and you'll be asked to select a host.
o	Select a host and check-in is done. Host will receive an SMS and an Email.
## To Check-Out

o	Access Running Entry Section of Page
o	Click on checkout and entry will be checked out. Guest will receive a mail regarding the meeting details.
o	You may also checkout from Entry Details screen which can be accessed by clicking on an entry in Running Entry Section of Page
## 	Past Entry

o	An entry once checked out can be viewed in Past Entry Section of Page

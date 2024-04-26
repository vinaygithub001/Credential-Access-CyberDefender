# InsiderChallenge
Scenario:
“After Karen started working for ‘TAAUSAI,’ she began to do some illegal activities inside the company. ‘TAAUSAI’ hired you as a soc analyst to kick off an investigation on this case.

You acquired a disk image and found that Karen uses Linux OS on her machine. Analyze the disk image of Karen’s computer and answer the provided questions.”

An essential tool we use in disk analysis is FTK imager, and that’s the tool we will need today to start the investigation.

Q1. What distribution of Linux is being used on this machine?

Kali
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/0f1e3c8a-5119-44b8-bc84-473541c4cb83)

Q2. What is the MD5 hash of the apache access.

d41d8cd98f00b204e9800998ecf8427e
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/ba990c0c-0081-4b4b-8dc2-876e0261d175)

Q3. It is believed that a credential dumping tool was downloaded? What is the file name of the download? \

mimikatz_trunk.zip
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/d202b5c7-e57b-4048-8f5b-3b9744bd0cde)


Q4. There was a super-secret file created. What is the absolute path?

/root/Desktop/SuperSecretFile.txt
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/6cc57255-f520-4881-8d05-bd11b1a0a6e9)

Q5. What program used didyouthinkwedmakeiteasy.jpg during execution?

binwalk
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/9a8af6dd-4a01-48da-8cb2-89dd618e15de)


Q6. What is the third goal from the checklist Karen created?

profit
![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/30933cd0-0a98-4f44-b5a2-85357b1e73a8)

 Q7.How many times was apache run?
 
 zero times

 ![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/8fe06faa-7d1f-45ef-b3bd-64cab7ae2123)

Q8.  It is believed this machine was used to attack another. What file proves this?

irZLAohL.jpeg

![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/f99aef42-215c-4b26-85d0-d6e5ba56a902)


Q9.  Within the Documents file path, it is believed that Karen was taunting a fellow computer expert through a bash script. Who was Karen taunting?

![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/e34b4228-3393-46cd-8855-3bae20e7a1b4)


Q10.  A user su’d to root at 11:26 multiple times. Who was it?

one

![image](https://github.com/pulgamvinay/InsiderChallenge/assets/100342550/70ff9342-73e5-4820-be56-954d8fa61b62)

high-five ✋



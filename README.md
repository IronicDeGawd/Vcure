## GEEKATHON 1.0
https://webathon.devfolio.co/

## Problem Statement
Design a secure and transparent blockchain-based voting system for elections or decision-making processes. Ensure anonymity and integrity in the voting process.

## Proposed Solution
* We'll be building up the voting system on the polygon blockchain to bring transparency and security 
* Usage of polygon blockchain will ensure lower transaction validation times and gas fees 
* The platform would be available for android, ios and web since it would built be using flutter which supports multiplatform and provides pleasing ui/ux for the users
* Once the user vote, a unique hash id using SHA256 algorithm, will be generated using the voter id, public address and registered phone number with id of the user which will be mapped to true and checked each time a user tries to vote ensuring that each citizen could vote only once and not create multiple wallets to vote

"VoterID"+"PublicAdress"+"PhoneNumber" --sha256--> UniqueID
    <img src="https://github.com/IronicDeGawd/Vcure/assets/91710612/0ea750ac-fcb6-4be4-8289-c74b9fb9cc16">

  This hash generated for citizen would be mapped to true. First 10 characters are voter id no, next 42 characters are public address and last 10 characters are phone number.
  
* E-KYC would be performed using registered phone number for extra security

## UI of App

<img src="https://github.com/IronicDeGawd/Vcure/assets/91710612/6f8ceb3f-4138-46e3-8b9c-48a5d788086f" height="524">
<img src="https://github.com/IronicDeGawd/Vcure/assets/91710612/f5bf5c4d-f8d3-421f-90e3-c3f205efb114" height="524">

## Team Member Details

* Aditya Srivastava | [Linkedin](www.linkedin.com/in/aditya-srivastava-ironic/ "Linkedin") 
* Ashiya Rana | [Linkedin](https://www.linkedin.com/in/ashiya-rana-8ba667251/ "Linkedin")
* Prithvee | [Linkedin](https://www.linkedin.com/in/prithvee-ojha-0290b0267/) 
* Kirti Chauhan | [Linkedin](https://www.linkedin.com/in/kirti-chauhan-24ab4b249/)

## Process Flowcharts
##### Account Creation
<img src="https://github.com/IronicDeGawd/Vcure/assets/91710612/cadc6e09-5bc1-42d8-8e04-979e46321aad" height="724">

#### Voting 
<img src="https://github.com/IronicDeGawd/Vcure/assets/91710612/07ffcdb9-393a-43de-b46d-9a62f3a8b881" height="524">



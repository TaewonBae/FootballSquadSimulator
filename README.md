# FootballSquadSimulator Demo Video

[![fss_img](https://user-images.githubusercontent.com/43931412/206648238-ff09655a-106e-4861-886e-140ed4fbbd3b.png)](https://www.youtube.com/watch?v=dxtBo5Kp3P0)



***
# What is FootballSquadSimulator?

*HellSchedule is an application that reads different people's body type and introduce them how to exercise according to body type.*
*You may have experience in forming squads through FM or FIFA Online.*

### 1. Description
- There are 25 players in the game.
- User have to pay a certain fee to transfer a player.
- Users can choose their preferred players.
- User have to make a squad within $15
- Warning message will be printed if the value exceeds $15
- Make your own best squad!
- You can enjoy it on the WEB in 3D!
![img1](https://user-images.githubusercontent.com/43931412/206649262-3d9e8576-5efd-46c9-99d5-cde0b72459d8.png)


* This application will help you to plan your exercise.

* Attendance is recognized if you stay at a place similar to the gym through the user's location for a certain period of time.

* You can easily know your body type. (fat, skinny, healthy, lower body obesity, upper body obesity)

* You don't have to think about how to exercise anymore. 

* It is to give you a walkway and a variety of health knowledge.

* You can see the knowledge of exercise and health regardless of time and place.




***
# Process
1. Detects users location and checks if users are at the gym or not.
1. Read body information(height, weight, skeletal muscle, BMI, etc.) using OCR. 
1. Analyze a person's body type.
1. Store people's information in DB.
1. Tell people how to exercise according to their body type. (exercise is stored in DB) 
1. Based on the location information of the gym and house, recommend about the nearby walkway.

***
# Development Technology
* Application Service - Android Studio
* Reading body info - Optical character recognition(OCR)
* Detect user's GPS - Google Location Services API
* Store User's info and exercise in DB - DB Browser || Firebase
* Collect Data (walkway, body type, etc.) - from https://www.data.go.kr/[Data Portal]

***
# Developer

Moon Seong-Hoon
foxtail96@naver.com
Gachon Univ

Park Ki-Sung
96sean@naver.com
Gachon Univ

Bae Tae-Won
grrard1283@naver.com
Gachon Univ

Choi Han-Bin
wkgkskak@naver.com
Gachon Univ

***


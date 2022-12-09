## FootballSquadSimulator Demo Video
*Click on the image below to play the demo video.*

</br>

[![fss_img](https://user-images.githubusercontent.com/43931412/206648238-ff09655a-106e-4861-886e-140ed4fbbd3b.png)](https://www.youtube.com/watch?v=dxtBo5Kp3P0)

</br>

- Select and place the competitor in the desired position.
- If you select a duplicate player, you will receive a warning message.
- The balance in the upper left corner of the table will be reduced as the player is recruited.
- An error message is output when the balance is exceeded.
- If you form a team, you will be able to do the squad that you made
- You can see it at different angles and locations.


## What is FootballSquadSimulator?
<img src="https://user-images.githubusercontent.com/43931412/206649262-3d9e8576-5efd-46c9-99d5-cde0b72459d8.png"/>

*You may have experience in forming squads through FM or FIFA Online.*
*You can enjoy it on the WEB in 3D!*


### 1. Description
- There are 25 players in the game.
- User have to pay a certain fee to transfer a player.
- Users can choose their preferred players.
- User have to make a squad within $15
- Warning message will be printed if the value exceeds $15
- Make your own best squad!
- You can enjoy it on the WEB in 3D!

</br>

### 2. KeyFeature

</br>
![img2](https://user-images.githubusercontent.com/43931412/206653875-fc2e5231-27e3-4740-9648-fd011375f28f.png)


</br>

- All players are modeled in 3D, and they can be viewed from various angles by implementing a camera vision.
- The Light Source is fixed in the upper right corner, and you can see that it is applied in a variety of ways depending on the viewer's perspective. 
- You can now see the light source applied to the stand position.
- We expressed it more realistically by applying scaling to match the actual players' height.
- Translation can be applied to keyboard events to place players in the desired position, and rotations can be used to rotate players.
- 
</br>



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



</br></br>

***
# Developer

Moon Seong-Hoon
foxtail96@naver.com
Gachon Univ

Bae Tae-Won
grrard1283@naver.com
Gachon Univ

Choi Han-Bin
wkgkskak@naver.com
Gachon Univ

***


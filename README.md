# AR_Book_Cover_Soumya

The required folders and files are there in this repo. The generated folder and files and the Xcode files for iOS development are not included with this repo because of size restriction by GitHub. There is only script in the Assets/Scripts folder which is actually controlling all the AR buttons at the back cover of the book. This sccript is actually enabling and disabling some gameobjects in the scene window whenever an user hits various buttons on the back cover of the book.

This script is very simple by nature. There are three buttons on the back cover of the book. The first one will show the user some real pictures. The second button will show the user some relevant short information about the book, and the last button will give the user a little bit more overview of Franklin, Tennessee with a picture taken from the book. There is no proper check of various conditions as most of the conditions are very obvious by nature while interacting with the buttons. If a person interact with one button then I am disabling other buttons so that he/she cannot able to interact with other buttons simultaneously. I did this because I thought a person cannot see more than one functionality at the same time. Also, I use simple Unity UI buttons for interaction. I first started with Vuforia AR buttons, but later I found that it is very hard to interact with those buttons if the tracking space is not good. In my case, my back cover of the book is not a good tracking space. So, I changed the Vuforia AR buttons to simple Unity UI buttons.

The reduced version of the whole Unity project is there in the GitHub repo. If someone wants to experience the whole Unity project then he/she can get it from the following link
https://drive.google.com/open?id=1a89oqGw7S0uwIrVfjJgijC2giYfHlFBV
In the reduced version of the Unity (which is included in this repo), the user needs to activate the Vuforia Augmented Reality support in the Project Settings -> XR Settings. Also depending on the Android device or iOS device of the User, he/she needs to change the build settings of this project to the respective device support and also he/she needs to change the project settings respectively based on his/her mobile device OS.
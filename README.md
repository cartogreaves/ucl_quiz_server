# Location Based Quiz - Setup and Server
The overall aim of this project is to create a location based quiz as an android application, where the users location is a key component is using the quiz. Using bitvise as a FTP, repositories have been created for both **[quiz mobile application](https://github.com/RJHCarto/Quiz)** and **[question web application](https://github.com/RJHCarto/Questions)**. Material design lite framework has been manipulated to create responsive, clean and aesthetic applications.

Components necessary include:
- **[Node.js - httpServer](https://github.com/RJHCarto/Server)**
- **[Question 'Creator' Web Application](https://github.com/RJHCarto/Questions)**
- **[Quiz 'Quizlet' Mobile Application](https://github.com/RJHCarto/Questions)**

## Installation guide
### Server
Firstly,  clone this github repository using the following command in bash.
```
git clone https://github.com/RJHCarto/Server
```
Next, get to your server repository in bash.
```
cd Server
```
Finally, start running your server remember to use a '&' to run in the background.
```
node httpServer.js &
```

### Question Application
You must clone this repository, follow **[this](https://github.com/RJHCarto/Questions)** link.
```
git clone https://github.com/RJHCarto/Questions
```
Next, ensure your httpServer.js is running, as per previous instructions.
```
cd Server
node httpServer.js &
```
Intialise phonegap from the 'ucesrh1' folder within the questions repository.
```
cd ..
cd Questions
cd ucesrh1
phonegap serve
```
View the web application here: https://http://developer.cege.ucl.ac.uk:31290/

### Quiz Application
Access this mobile application via **[this](https://build.phonegap.com/apps/3154790/share)** link, or via the QR code below. You may need developer settings turned on, see **[this](https://developer.android.com/studio/debug/dev-options)** guide.

![alt text](https://github.com/RJHCarto/Server/blob/master/AppQR.png)

Next, ensure your httpServer.js is running, as per previous instructions.
```
cd Server
node httpServer.js &
```
You will now be able to open the application in Android. 
Access the user guide in app to find out how it works.

## Repositories of interest
Links to the following tools used for this application:
- **[Node.js](https://github.com/nodejs)**
- **[PhoneGap](https://github.com/phonegap)**
- **[Material Design Lite](https://github.com/google/material-design-lite)**
- **[Leaflet](https://github.com/Leaflet/Leaflet)**

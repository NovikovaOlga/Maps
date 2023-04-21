# Maps

## 🧟‍♂️🗺️ Working with maps: Apple, Google, Yandex. 

## Description
<p> The application is designed for demonstration maps: Apple, Google, Yandex, for example, the popular game. </p>

<p>
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/Demo1.gif">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/Demo2.gif">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/Demo3.gif">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/screen1.png">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/screen2.png">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/screen3.png">
 <img style="width: 180px;" src="https://github.com/NovikovaOlga/novikovaolga/blob/main/Other/Maps/screen4.png">
<p>

## Capabilities 
- The application uses animations:
    - an animated splash screen at the entrance.
    - animated app login button.
    - animated pulsating position of the user.
- Three tabs are available:
    - the map is based on cards from Apple, with fictional locations objects
    - the map is based on Google maps, with fictional locations objects
    - the map is based on cards from the popular fictional locations of objects.
- Each map displays a fictional animated location of the user.
- Map scaling is available on each map.
- A button to return to the user's location is available on each map.
 
## Technologies
 - **MapKit**
 - **GoogleMaps**
 - **YandexMapsMobile** 
 - **CoreLocation**
 - **Contacts**
 - **Animation**

 ## Privacy
 The application will ask for access permission:
 - **Location**
 
 ## Libraries
 ```
 pod 'GoogleMaps'
 pod 'YandexMapsMobile', '4.0.0-lite'
```
 
 ## Installing and launching the application
 
- You will need to install the framework
    - go to the application folder in the terminal
     ```
   cd [location of the project folder]
    ```
    - install pods
    ```
   pod install
    ```
    - Project startup file: .xcworkspace

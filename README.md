# IOT-Mountain-Climber-Monitoring-System
Iot Project for Mountaineering Gps Tracker using more than 3 sensors to track the health of CLimber
the project has to keep track of the climber's health with any changes that might put climber's health to danger the data are sent to server to be analyzed and we notify rescue team

BY using heart sensor (MAX30100) we collect user heart pulse
By using temperature sensor (Dallas) we collect user Body temperature
bY USING GPS SENSOR WE ARE ABLE TO KEEP TRACK OF CLIMBER'S LOCATION if they go offline we can notify the rescue team with the climber's latest location.


Climber gets to the Mountain.
 Start climbing .
To know the most occurring accident zone(s) we will collect data including temperature, altitude, heart pulse constantly using sensors and send them to server while the climber is climbing. These data will help us to know what rates a climber’s body is mostly having before the accident occurs
Our analysis according to the data that will be collected will help us to know the symptoms that show up in a climber’s body in a short time before the accident.
So far, sensors will still be collecting data as climber keeps climbing and if climber’s body starts showing same symptoms as most climbers have in time of accidents or even nearer the server will notify the rescue team that the analyzed data results are exposure or nearer to accident even if the climber will have not yet reached that most accident occurring zone because the GPS tracker will also be showing current location of the climber so may the rescue team reach in time to prevent the accident or any support could be provided in the right time.
![image](https://user-images.githubusercontent.com/88845756/213484888-c4480f58-799d-4283-8de4-a528b110bbbf.png)


data visualization 


![image](https://user-images.githubusercontent.com/88845756/213485412-633f61cb-0819-47dc-9c78-a3c7dbee26d9.png)


data storage structure on firebase

![image](https://user-images.githubusercontent.com/88845756/213485580-b6d47fa1-8b11-4aab-9b0b-8f3f1237ea55.png)

COLLECTION ANALYSIS
![image](https://user-images.githubusercontent.com/88845756/213485689-49f08127-edba-4ef9-8587-b665e5f6859b.png)


PREDICTION ANALYSIS BY USING DECISION TREE J48 USING WEKA SOFTWARE


![image](https://user-images.githubusercontent.com/88845756/213486003-b986640c-1e2b-4f08-a849-c820bb653546.png)


Message sent to rescue team with code of Emergency (BLUE for risk but not too far, RED for very emergency)
![image](https://user-images.githubusercontent.com/88845756/213486357-c8699113-801d-4a88-8a23-162f1a34b617.png)



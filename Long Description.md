# Long Description
Objective of the App: To analyse users’ daily habits so that when anomalies are detected, CFRs could be mobilised for early intervention should the anomaly be an incident that requires a response.

Features of the App:
Methods of Detection
Location Tracking (Determines habits)
Smart Device Usage (Tracks based on how often you use your smart devices)
Facial and Posture Recognition (Detection of stroke, bleeding, etc.)
Background Analysis (Interpretation of background image to determine threats)
Alerting Functionality
Notifies and prompts the user to acknowledge whether the situation is true/false
Should a certain time limit exceed, it will proceed to notify a designated emergency contact
Should there be a lack of response for an extended period of time, it will then proceed to be highlighted to CFRs or will dial 995 depending on the severity of the incident
Habit Analysis
Will first be calibrated over the first week of usage. However, following weeks of usage data will be continually added to the dataset for further analysis
E.g. A desktop camera will analyse the amount of time spent by the user in front of the camera or away from the camera. When the user is away from the camera, the application will prompt the user to:
Check whether the user is okay
Seek feedback on what activity the user is performing so that better habit analysis can be done
An ecosystem of sensors will allow for a complete view of the user’s habits
Camera placed in a frequented location in the house
Motion, Sound, Light and Location detection from the user’s devices (e.g. Desktop computer, Laptop, Phone, TV, Smartwatches)
Screen time on user’s devices
The data will be trained by first inputting the average habit data of a Singaporean
The data received from the ecosystem of sensors will help refine the habit data of the individual
Past data will allow for prediction of various events (e.g. the user now left the camera view for 1 hour at 11.13am and the phone seems to be used -- user is having Lunch)
However, if the user is away from a majority of devices for an extended period of time such that the data model is unable to fit any event, it will deem it as an anomaly and perform its alerting functions
Should the user be away from their camera and using main
Method of Habit Data Storage
User’s habit events will be stored individually
Each time the application predicts that a certain event occurred (e.g. User went to the toilet at 10.43am for 15 minutes), the event will be saved under a specific Habit Category (e.g. Toilet Usage) for further analysis
Each event will be able to be confirmed by the user as affirmative feedback

Habit Model
Estimates when the user goes to the toilet
Phone Usage: High (this user uses his phone a lot when he goes to the the toilet)
Ambient Light Information: Range of values that qualify
Duration: 20 minutes

Habit Event:
Title: Toilet
Date: 6/13/2020
Day of the Week: Monday
Time Interval: 11.03-11.18am
Location: Your house
Duration: 15 minutes
Phone usage: 10 minutes
Camera Appearance: Is ryan in the camera? (Y/N)
Ambient Light Information:
Sound Information:
Amount of Motion detected by phone: 

Cons of the App:
Potential Privacy and Security lapses - Database may be bridged to review sensitive and private information. Users may also be deterred from using such app due to concerns of privacy infringement.
Fair point, can’t really be countered; therefore users will have to agree to the terms and conditions before using the App.
Requires the use of smart technology - Older users may not have access to such technology allowing some to ‘fall through the cracks’
As the solution is for a problem that we would face in the future, most of the current generation is attuned with smart technology and therefore we will be facing a generation of elderly who are well aware of how to use smart technology
Possible scenario where there is an inconsistent volume of data collected from users - App has to be configured to recognise scenarios when users decide to go for a long haul journey over an extended period of time
Easily solvable
Habits change over time - this may result in an incorrect analysis of data. Also, short collection of one week of data may not be representative of actual habits
Practical issues - Battery, Requirement of cameras and sensors, GPS connectivity

Prototype: 
Laptop Camera
It detects when the user is in front of it
If the user is away for more than 15 minutes (average time I take to use the toilet)
The app will notify the user’s phone asking them if anything is wrong
If no response, 
Within 1st threshold, contact emergency contact
2nd threshold, contact 995 or CFRs
If responded, the camera will track when the user next comes into view of the camera so that it can log the period of time that the user was away from the camera as data of how long the user went to the toilet
Based on multiple periods of time that the user disappeared from the view of the camera, it can train the model to understand when should emergency services be notified

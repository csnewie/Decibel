# Decibel

🔊Decibel: Real-time Noise level Measurement


#Inspiration
The city life is not only fast but extremely draining due to the constant noise, be it in traffic or due to ever present construction.
High noise is extremely deterrent to a healthy life and it causes issues like lack of sleep, migraines and difficulty in concentration.
Decibel helps us to use the mobile as a sensor, here we implement noise levels, but the functionality could extend to any attributes that the mobile is capable of recording. (for example: using the camera, accelerometer, gyroscope, etc)  
Decibel helps its users to record the noise to measure the db levels. Exceeding db levels will be reported to the concerned authorities who can help to curb it.

#Features
Real Time Application
Sound Recording in background
Decibel Measurement.
Storage on Cloud(MQTT) to save user device memory
Processing on cloud(Firebase)

#Demo
Messages getting published to Cloud MQTT upon recording



Data getting sent to Firebase from Cloud MQTT 





Email sent as alert .. because decibel level is high


#Usage/ Architecture
The user starts the Sound Recording with a button.
The noise is processed in the app and the db levels are measured, along with getting the location.
Measured db levels are sent to be stored on the MQTT cloud
The db levels are categorized and sorted in Firebase.
If the noise levels are hazardous for human-beings or other fauna, the concerned authorities will be notified.
Notifications will be sent in the form of emails through firebase.









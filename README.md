# Active-Drive
Sleepy Driver Detection Application for Active driving

It is an application that continuously monitors driver’s facial landmarks and based on that it alerts driver in real-time if he is found 
sleepy. Application needs the alarm file and shape_predictor_68_face_landmarks.dat file to run successfully. Also, I used Twillio's service for messaging, so account sid, auth_token, and phone number needs to be replaced. 

Active-Drive, is designed to detect the fatigue or drowsiness and restores driver’s attention on road by continuously monitoring driver’s
eyes and alerting the driver in real time by alarming a loud siren to wake the driver immediately. Moreover, Active-Drive sends a text 
message to the registered mobile number of a friend, this feature can be used for personal and for commercial vehicles, 
where logistics company fleet managers need to know which driver is not driving cautiously and can prevent loss of life and money.

Software tools and Libraries: 
OpenCV (Open source computer vision Library)
Python
DLib 
Twilio - messaging webservice is used to send text messages

References:
[1] OpenCV: https://opencv.org/
[2] DLib C++ and Python library: http://dlib.net/
[3] Twilio messaging services: https://www.twilio.com/
[4] Real-Time Eye Blink Detection using Facial Landmarks by Tereza Soukupova and Jan Cech at Rimske Toplice, Slovenia, February 3–5, 2016. 

The trained model named shape_predictor_68_face_landmarks.dat we are using was an trained model which uses Histogram of Oriented Gradients feature combined with a linear classifier, an image pyramid, and sliding window detection scheme
[5] http://dlib.net/face_landmark_detection.py.html
[6] https://ibug.doc.ic.ac.uk/resources/facial-point-annotations/


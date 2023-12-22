# Blind-Assistant-System

The idea of this project is to assist visually impaired people in their daily activities using “Blind assistant using Computer Vision”. The project will be able to read text from images, detect objects, and also detect people around. The device would be a voice-enabled system that would direct the visually challenged person in their day-to-day work. For ease of use for blind people, voice-based input and output are added.

## User Interface
The proposed system was implemented using the Flask framework and tested on various image datasets. The system was able to successfully detect and classify objects in real time with an average precision of 0.87 using the YOLO model. The text reading module was able to perform OCR on images and accurately read out the detected text to the user.

![home-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/c03917e1-1f0d-478e-abf0-56e39703ad60)

The above figure shows the home page of the web application. The home page consists of a navigation bar that can be used to navigate to the object detection page or text reading page. This navigation can be done by voice command by the blind individual.  

![object-detection-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/4faa19d5-4056-41d5-b11d-def6fb827952)

The above figure shows the object detection page of the web application. The application gives voice feedback on the detected objects near the user when a voice command to describe the environment is given.

![text-reading-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/2d79ec1b-380c-40a3-b92b-caedaa0a925c)

The above figure shows the text reading page of the web application. The application reads aloud the detected text to the user when a voice command to read text is given.

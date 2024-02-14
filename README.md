# Blind-Assistant-System
Author Harshali Patil
The idea of this project is to assist visually impaired people in their daily activities using “Blind assistant using Computer Vision”. The project will be able to read text from images, detect objects, and also detect people around. The device would be a voice-enabled system that would direct the visually challenged person in their day-to-day work. For ease of use for blind people, voice-based input and output are added.

## User Interface
The proposed system was implemented using the Flask framework and tested on various image datasets. The system was able to successfully detect and classify objects in real time with an average precision of 0.87 using the YOLO model. The text reading module was able to perform OCR on images and accurately read out the detected text to the user.

![home-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/58a91693-b2fb-4773-ad3a-a8aea0ab0e2d)

The above figure shows the home page of the web application. The home page consists of a navigation bar that can be used to navigate to the object detection page or text reading page. This navigation can be done by voice command by the blind individual.  

![object-detection-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/cf1b6fcc-266e-4ddf-b27c-1e09bcf980a2)

The above figure shows the object detection page of the web application. The application gives voice feedback on the detected objects near the user when a voice command to describe the environment is given.

![text-reading-page](https://github.com/harshali-patil29/Blind-Assistant-System/assets/129577409/039c5363-7546-4407-84c7-cd4853d0e910)

The above figure shows the text reading page of the web application. The application reads aloud the detected text to the user when a voice command to read text is given.

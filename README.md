# TheAttendanceMaster (:TAM:)
----p.s. the colons in the acronym above are there to make it look like there are two smiley faces next to it.----
#
The prototype that we have created is only a fraction of what we believe this could be... Our goals for the prototype are very simple. The phone is first inserted into a case so that it stands straight and points toward the door, and the teacher can easily take pictures. Everytime the door opens, the teacher just has to click a little button and it will take a picture. The app then analyzes the picture, using microsoft's face detection api and returns a uniqe id. Each person in the class have an id. The app then compares this id with every person in the class, and finds out who entered the room and records it. When the teacher would normally call roll, he/she just has to press a button and he/she knows exactly who came and thereby saves at least 5 minutes.
# We seperated the app into 2 parts and then we merged them together: The camera and the facial recognition:
# THE CAMERA:
Takes a picture and saves it (not too challenging)
# THE FACIAL RECOGNITION: 
Uploads a picture from your gallery (taken pictures), puts the picture on the screen, draws a rectangle around it, and returns the face id. If you are looking for a tutorial on how to do this, I used https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiinjavaforandroidtutorial and only added the part where it returns the face id.

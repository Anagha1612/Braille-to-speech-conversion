# Braille-to-speech-conversion

The design/programming methodologies include the following modules:
1.	Creating an user friendly interface: The user would be able to convert braille into speech here.
2.	Braille image acquisition: The user can directly upload braille scripts of their choice for conversion.
3.	Image processing using OpenCV: The Braille input image should be processed in the way that is convenient to read and it is done by using methods in OpenCV (Open Source Computer Vision) library which is primarily aimed toward a real-time PC vision. To identify the braille letters, we will use an OBR model with our dataset. 
4.	Text to Speech: The Braille script to voice conversion explores a python module that translates braille input images into text which is in turn converted to speech and vice-versa, using gTTS API and pyttsx3 library. The principal objective of this task is to set up a means of reading comprehension for specially-abled people.

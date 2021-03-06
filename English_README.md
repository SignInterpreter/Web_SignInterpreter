# Web_SignInterpreter

## Summary

This project would provide an efficient sign interpreter through your camera device. Our first goal consists of developing the classic game "Rock, paper, scissors", thanks to the framework
mediapipe which benefits from machine learning to recognise hand's gestures and convert them to a message.

Once we accomplish this objetive, we want to escalate our project for being able to recognise sign language and display the message on the screen in real time. This would be an
awesome tool for people who are unable to use verbal communication to make themself understood easier.


## Developers

Eduardo Rodriguez => https://github.com/EduardoRodMol

Borja Espés => https://github.com/BorjaEACode

## Dataset
The dataset has been created by us, using mediapipe and opencv, capturing the images of both hands and storing them which its matching label.

## Sources

- https://google.github.io/mediapipe/solutions/hands.html
- https://developers.googleblog.com/2021/04/signall-sdk-sign-language-interface-using-mediapipe-now-available.html
- https://laptrinhx.com/mediapipe-hand-gesture-based-volume-controller-in-python-w-o-gpu-1503882022/
- https://medium.com/analytics-vidhya/mediapipe-fingers-counting-in-python-w-o-gpu-f9494439090c
- https://github.com/Kazuhito00/hand-gesture-recognition-using-mediapipe/blob/main/README_EN.md

## Web use

If you want to use our app directly browsing a website, you are lucky!, we have deployed our app on Heroku's platform, so click on this link. Now I will guide you through the different pages that you can choose in the column on your left.

### Main Page

Here you can find a brief sumary about the proyect, information about the dataset and our github's accounts.

### Game

Here you can play rock, paper, scissors against the computer.
First of all, click on the run button, a window will pop up where you must hit SELECT DEVICE, after this allow the browser to use your camera, once done you can choose which of your cameras you want to use. When you have choosen it click on DONE, you should go back to the initial window, then hit the START button, now you should see your image on the screen and the game will begin.
When you want to stop playing just click on the button STOP and the camera will be shutdown.

### How does it work?

Aquí explicamos como funciona Mediapipe, que es el framework que hemos utilizado para captar los keypoints de la mano y así saber la posición de los dedos e identificar las diferentes opciones de piedra, papel y tijeras.

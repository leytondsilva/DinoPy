# DinoPy
A naive python bot that plays Google Chrome's Dino game.

#### Link to Dino game (simply copy-paste this into Chrome's url box):

chrome://dino

<img src=img/DinoPy.png width=500 height=350>

## Requirements:
1) Python
2) Python Libraries:
* Pillow
* Numpy
* Pyautogui

  
Pyhton Download : https://www.python.org/downloads/

### To download Python Libraries:

1)Open CMD

2)Type (pip install library_name): 

  * pip install numpy
  
  * pip install pillow
  
  * pip install pyautogui
  
## Steps:
1] Align the chrome tab to the left.
<img src=img/Align.PNG width=500 height=350>

2] Hit SpaceBar and take a screenshot using Win + PrintScreen.
<img src=img/Start.PNG width=500 height=350>


3] Find the area of pixels in front of the dino to detect obstacles.
  * Ceate a rectangle box ahead of the dino
  <img src=img/Rect.PNG width=500 height=350>

  * Hover over the corners to find the X, Y Coordinates
  <img src=img/Area.PNG width=500 height=350>
  <img src=img/Area2.PNG width=500 height=350>

  



4] Edit the pixel coordinates in the py file.
<img src=img/Edit.png width=500 height=350>


5] Run and optimize it to your preference.

**[Back to Top](#DinoPy)**

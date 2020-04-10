# AutoDrawer
A program made in Python 3.7 that automatically draws an image using OpenCV and Pynput. Made to work with Paint, but it can also work with other drawing tools.

# How to use
<img src="https://github.com/GustavoMuller2019/AutoDrawer/blob/master/examples/interfaceExample.png?raw=true">
<img width="200" height="200" src="https://github.com/GustavoMuller2019/AutoDrawer/blob/master/examples/original.png?raw=true"><img width="200" height="200" src="https://github.com/GustavoMuller2019/AutoDrawer/blob/master/examples/drawed.png?raw=true">
<br><br>

Open the program and paste in the URL of the image or select one from your computer.
Then, customize all the drawing parameters you want. You can preview the image, the thresholded image
and the contours the program will draw with the 3 preview buttons at the bottom.
Once you're satisfied, click the draw button. After clicking, the program will start drawing in 3 seconds,
so make sure you already have Paint opened up beforehand.
After the 3 seconds, the program will record the position of your mouse. That position will be the top left corner of the image.
Finally, the program will minimize and will start to simulate mouse presses/clicks to draw on the screen.

# Libraries Used
Contour Recognition: OpenCV<br/>
Interface: PySimpleGUI<br/>
Drawing: Pynput<br/>

Other libraries:<br/>
Time, Winsound, Numpy, urrlib.request, skimage.io, keyboard

# Learn more
If you don't understand what all of the image parameters are, make sure you read about them at https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_setup/py_intro/py_intro.html#intro.

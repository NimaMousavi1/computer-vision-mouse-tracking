The video transmitted by the camera is analyzed image by image in real time. The first method is based on edge detection. In this method, the edges of the mouse are detected by an edge detection method. In this method the the Orange color is taken to detect an edge of a mouse. Any object of orange color whch lies at arange of (5 to 15 HSV) can be taken. When the web camera started every object aside from orange color wll be black. Only object with orange color will be available.

The second method for mouse detection and tracking method that we describe is based on color analysis. In this approach an object with orange color is placed in front of the camera.This is known as reference mark. This mark is used as the reference point of the mouse. Whenever the object is moved by the user the location of the reference point changes. The detection of the reference point can be carried out by adaptive thresholding. By tracking the reference point the cursor is moved by the computer as described above. This color coding approach is easier and more robust then the edge detection method as the viewing area of the camera is more or less known by the image analysis system

The third detection and tracking approach is based on motion analysis. WE will achieve it through by using the above 2 methods with pyautogui to move the mouse based on its colors.

Orange - Cursor movement

Green - Left-Click

Yellow - Rght-click

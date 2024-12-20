**Overview**

The experiment utilizes Python with the OpenCV library to iterate through all possible RGB levels in grayscale, capturing screenshots of each gradient. Detected differences are logged and analyzed to calculate the average differences between the levels. 
20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64, 65, 66, 67, 68, 69, 70, 71, 72, 73, 74, 75, 76, 77, 78, 79, 80, 81, 82, 83, 84, 93, 95, 102, 120, 140, 156, 189, 203, 227, 240, 245, 250 
This level was seen because of the monitor.

**Comments**

The level detected here is quite high. Brightness changes were noticed on the laptop screen, and these differences were recorded as the noticed level. An important detail is that the detected levels were detected on the laptop screen, although this process was not detected on the monitor screen even though there was a 23.6 inch gaming monitor. Another important detail is that as color images become grayer and the time spent looking at the screen increases, eye fatigue begins to be felt. More detectable details may not be detected due to eye fatigue. Detection of difference levels was carried out under white light. The experiment was carried out by implementing the opencv library in Python language. First, screenshots from (0,0,0) to (255,255,255) were recorded and then the difference detection process was performed. Another important detail is this: While it was easier to distinguish the color on the full screen of the laptop, when screenshots were added to the report, the difference in perceived levels seemed not to be perceived.

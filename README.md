# Color_detection
## Brief Summary
### About
Built an application through which the name of the color can be automatically obtained by double clicking on it. 
For this, used a data file that contains the color name and its values. Then, calculated the distance from each color and find the shortest one.

### The Dataset
Colors are made up of 3 primary colors; red, green, and blue and I used a dataset that contains RGB values with their corresponding names. 
The CSV file that I used for the dataset is named as "colors.csv". The colors.csv file includes 865 color names along with their RGB and hex values.

### Steps
1.) Used three files to build the application:
    (a) Color_detection.py – main code of the project
    (b) Colorpic.jpg – sample image for experimenting
    (c) Colors.csv – a file that contains our dataset

2.) Worked on the detection of a particular color in an image. I have written a code which will work to detect red colour in the entire image (File name - Detect_red.py)

3.) Written a code to change the brightness and contrast of images using Opencv Python (File name - Slider.py)

# Color-Detection-codeclause
An interactive app to detect the colors on double click.

![image](https://user-images.githubusercontent.com/108170869/231941136-13faaaea-109e-4868-96f8-cc737c520239.png)


This is a color detection program that allows users to identify the name and RGB values of any color in an image. The program uses the OpenCV library in Python to read an image and resize it to a desired size. It then reads a CSV file containing color names, hexadecimal codes, and RGB values, and creates a function to calculate the minimum distance between a user-selected color and the colors in the CSV file. The program displays the selected color's name and RGB values in a rectangle on the image. If the selected color is very light, the program displays the text in black color.

To use the program, the user should have Python and OpenCV installed on their computer. They should also have an image file saved on their computer. After running the program, the user can double-click anywhere on the image to select a color. The program will then display the name and RGB values of the selected color on the image.

Note: To exit the program, the user should press the 'Esc' key.

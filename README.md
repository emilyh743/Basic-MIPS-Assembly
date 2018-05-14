# Basic-MIPS-Assembly

Computer Organization course assignment and MIPS.

ex1.asm

Program that computes the area of a rectangle given the width and the height and also calculates and prints perimeter.

ex2.asm

Modify the ex1.asm program in ex2.asm to make it work on multiple inputs. In particular, it should repeatedly ask for width and height values, and print the corresponding area and perimeter, until the user enters the value 0 for width. At that point, the program should terminate. 

ex3.asm

Assembly program to convert red-green-blue (RGB) values for a set of pixels into a single gray value per pixel.
For this exercise, read through the array of pixels, and for each pixel, convert the color pixel into a grayscale pixel using a simple formula: gray value = (red + green + blue) / 3. Note the division is integer divide and truncate (i.e., no rounding needed).

The calculation of the gray value should be done in a separate procedure called rgb_to_gray. (Note: For this simple task, there is no need to create and use a stack. This is because there are no nested procedure calls, and the calculation is fairly trivial, so no sophisticated management of register saves/restores is needed.) Just use the jal instruction to call a procedure, and the jr instruction to return from that procedure.

After calculating the gray value for a pixel, print it out to the console (only one element per line). The program keeps reading RGB values and printing the corresponding gray value, until it encounters an input of -1. The expected output format is given in the comments in the starter file on the course website.


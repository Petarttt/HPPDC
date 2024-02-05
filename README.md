# HPPDC
High Precision Pi Digit Calculator 
This program is designed for Linux and it may or may not work on other OSs.
You can input the precision and amount of CPU cores to use.
It works for atleast a few million digits of pi but may be slow for more than a few million digits.
The output of the program is to pi_digits.txt in the same directory

How to compile:
gcc -o calcv5 calcv5.c -lmpfr -lgmp

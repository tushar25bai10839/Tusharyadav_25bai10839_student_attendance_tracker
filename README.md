# Tusharyadav_25bai10839_student_attendance_tracker

Tkinter Calculator

A clean, simple calculator app made with Python… because sometimes we all just need to add things without opening Excel.


 What This Project Is About

This is a small GUI calculator I built using Tkinter.
It does everything a normal calculator should do:
add, subtract, multiply, divide — plus a couple of extra tricks like squaring a number or taking the square root.

The goal was to keep it simple, smooth, and easy on the eyes.

 What It Can Do
 Basic Math

Add


− Subtract

× Multiply

÷ Divide


➕ Extra Goodies

🔲 Square a number (x²)

√ Take square root

 Clear everything with one tap


⌨️ Keyboard Friendly

Type on your keyboard or click the buttons — both work.
Press Enter to calculate your result instantly.

The Look & Feel

I went for a soft, clean color palette — light blues, whites, and greys — so the UI feels calm, not cluttered.
The buttons stretch and resize neatly because the grid adjusts to the window.

Nothing fancy… just smooth and functional.

 How the Code Is Organized

Everything lives inside one Calculator class so it’s easy to manage:

Creates the display area

Adds all the number and operator buttons

Handles keyboard input

Updates what’s shown on screen

Does the math behind the scenes


Basically, the class controls the whole calculator.


 Running the App

1. Save the code as calculator.py


2. Run it from your terminal:



python calculator.py

That’s it — the calculator window pops up.

Behind the Scenes (Simple Explanation)

When you click a number → it gets added to the current expression

When you click an operator → it prepares the next part of the expression

When you hit = → it evaluates everything using Python’s eval()

Labels update instantly so you can see both the full expression and the current one


Nice, simple, and straightforward.

 Final Thoughts

This project is perfect if you want to learn Tkinter or build something visual without going too deep into complicated GUI programming.
It’s clean, readable, and easy to expand — add %, history, brackets, anything you like.
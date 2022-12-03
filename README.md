# Eye-Tracker
Detecting Eye Direction using Python

Project in
->Project
->Project executed
->LEFT_RIGHT_EYE

Two Branches
-> working
-> main



# Introduction
Many eye-tracking systems either require the user to keep their head still or involve cameras or other equipment mounted on the user’s head. While acceptable
for research applications, these limitations make the systems unsatisfactory for prolonged use in interactive applications. Since the goal of our work is to use eye trackers for improved visual communication through gaze guidance.


# Components
The eye tracking software consists of two main components: The image processing algorithms that are used to extract the location of the pupils and corneal reflexes from the image and the gaze estimation algorithm that is used to calculate the position the user is fixating on the screen.
 

# Gaze Estimation Algorithm
This algorithm uses gaze ratio of left and right eye, here we determine if a person is looking at the left then ratio of black and white pixels on (left pixel)/(right pixel) will be greater than 1,
if a person is looking at the right then ratio of black and white pixels on (left pixel)/(right pixel) will be less than 1.

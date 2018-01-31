# StonePaperScissors
A interactive Stone Paper Scissors game using openCV and python.

This Project includes real time involvement of a user who plays the Stone-Paper-Scissors game with the intelligent computer Bot. This bot readily recognises the hand gestures using trained Haar Cascades.
In a parallel thread there is a list of randomly generated stone|paper|scissors which it compares with the user as we do in real world.
According to sign priority (Stone>Scissors and Scissors>Paper and Paper>Stone), the player(bot or user) wins.

Requirements:-
1) Python 3
2) OpenCV- Through with computer vision module is implemented and hand gestures are captured.
3) HaarCascades- These are simple xml files which are trained over a set of positive images(images for which cascades are trained) and very large set of negative images(non-relatable images).


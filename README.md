# Youtubers-life-Save-Editor
A Youtubers life game save editor

# Progress:
25% done current status: An easy save editor wich can be used by the avarage player
The next step i want to implement are automatic patch and add easier ways than knowing the id for modifying things like the house

# Save format:
the save formatt has been discovered and it's quite simple:
save file is a simple .tsv compressed as a GZIP

# How to use it:
The usage of the programm is very simple
1 You load your save file
2 Yo do your modification thanks to the text editor
3 Save the file and reload it on the game

## help:
anyone can help :D

## story of the project:
Youtubers Life always had a special place in my heart (I've like 91.2 hours on the game) and when a friend of mine told me that he had 100+ hours on it i decided to show him that I was the biggest YL1 fan so I started this project
at first i was very confused i spent hours looking at a save file on my trusty hex editor but i couldn't understand anything but i did notice something, every save file started with "H4sIA" wich was familiar too familiar. Looking a bit futher in the file it made it clear it was a GZIP file masked as a .yls save. So i tried to decrompress it and it worked! I had a fully understandable .tsv file that i could modify however i liked and manageg to do some little modifications

I've included the set1.ipynb file that has all my work for this set.
I've included functions for many things.
I've left comments for many things that can be played with. 

Specifically, the data processing that takes in files, normalizes X, and crops
images is hamstringed currently by the count variable breaking the loop,
as well as the num variable that controls how many images per file to do. I 
had these due to system limitations encountered, but they can be changed to
use the whole dataset. Specifically, the break can be removed, and the num= can
be changed. 

Towards the bottom, I have my model classes, followed by the training code. 
Parameters like epochs can be modified as needed.

At the very bottom, I have code to run predictions, which generates the
confusion matrix and returns predictions along with the correct labels given 
X and y as defined in the spec

In my testing here, my model was able to achieve mediocre performance, likely
hampered by the amount of data my system could handle without jupyter crashing.
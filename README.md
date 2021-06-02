# Object detection project

Only works in Linux.

As it has been built from 0, it has been difficult to test whether all requirements get installed automatically by the jupyter notebooks (I advise using a python enviroment when executing them).  
  
## Labeling.ipynb  

It is not mandatory to execute Labeling.ipynb, its function is to take pictures with the web camera to use as the database, and then label them. I have already included 80 images as an example. They are located at Tensorflow/workspace/images/collectedimages. Each directory contains a different type of picture, with its correspondent label (the xml file).

If you want to execute it, you can choose whether to take photos or not. If your answer is yes, the program will instantly take a picture and show it to you; then, after you press any key, you will have 2 seconds to prepare for the next picture. It is set to 5 pictures for each category by default.

A new window will then open to let you label the pictures. It is a slow process, but if anyone wants to try it, feel free to ask me about how to do it.  

## Training.ipynb

After training the model, the program will show you the % of accuracy a picture has. You can manually choose what picture you want to analyze.
You can also test it in real time, a new window with your camera will open and it will try to detect any gesture shown.

Xavier Nadal Reales

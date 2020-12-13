# i-Lens :sunglasses:

## Introduction
This web application implements Tensorflow to allow people who are blind or suffer from sight *illness

# Installation
### For tensorflow
use this command to install everything tensorflow need:
```
pip install pillow Cython lxml jupyter matplotlib contextlib2 tf_slim
```
for more information about tensor flow can find out at https://www.mygreatlearning.com/blog/object-detection-using-tensorflow/

### Requirements
use this command to install all the requirements:
```
pip install -r requirements.txt
```
# To Run This Web App
use this command to run in streamlit: 

**Note that you have to cd inside the research file first**
```
streamlit run realtd.py
```

# Note
Some of the elements / widgets will not work unless you change the directory to your local machine directory.
eg. C://Document//research//images_text_detection
If the error file not found exist, they consider making the directory to absolute directory instead of relative.

# What it does?
- It can help to detect object in front of the blinds and instruct him/her to go left or go right.
- It can help to detect text and convert to speech.

# Current Cons
- Text detection to speech cannot be combine together in the real time obstacle avoidance system due to streamlit limitations, currently it is store as another file. In the future, text detection to speech will be implemented in the main application. 

# Demo
You can watch YouTube video link below about how our Web App work! 
(add link here)

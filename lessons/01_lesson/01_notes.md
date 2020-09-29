## Lesson 01 notes
Daniel van Strien's notes
These notes are very rough, I will try and come back and tidy them one day... 

### what's covered in the lesson?

- an intro to the course, library and fastai organization

### tl;dr (takeaways) 
These were some key takeaways from lesson 1 for me

#### Models give you predictions - don't tell you what to do. NOT creating actions, creating predictions 
It is really useful to be reminded of this from time to time. 

#### Models operate in an environment
Again I think this is something that should be considered all the time. There seem to often be two responses types of responses to the outputs of ml models from people, either the model is complete shit because it doesn't get a few predictions right, or it's amazing because of it only misses a few predictions. I think it's really important to consider what the 'environment' these predictions are operating in (i.e. some experimental project with a GLAM collection vs a live catalogue system). 


### How much data/how many labels?

Not enough labels? 
need for deep learning will almost always come from a lot of data
but not enough labelled data


A model operates in an environment - how does a model interact with the environment 

- where do we use ai in GLAM settings. which environments does deep-learning get deployed in? 

Biased data? 

- example from policing and arrests, feedback loops ? 

This is obviously an issue with GLAMs too, for example how extensive our certain things catalogued. this could be deeply harmful or relatively benign 

- Proxies - data is a proxy for something else you actually care about! 
- metadata can also be used as a proxy for something else 


### Python code

- import * makes some people sad but in fastai is done by defining `__all__` http://xion.io/post/code/python-all-wild-imports.html


### fastai aplications 
- vision
- text
- tabular
- colab filter 

Doc function can be used to find out what a function does. doc() 

Documentation is written in Jupyter notebooks :) so you can run the documentation examples? 

Library written in nbdev which is *chef kiss* 






# image_analysis_example

# -*- coding: utf-8 -*-
"""
Created on Mon Aug 26 16:40:52 2019

@author: jhodges

1. Download: 
    python: https://www.python.org/downloads/
    git bash: https://git-scm.com/downloads
2. Add python to your path
3. Open a command prompt and install packacges
   A. pip install opencv-python opencv-contrib-python spyder
4. General algorithm:
   A. Background subtraction to identify where the ball or droplets are
   B. You may want to use binary dilation or erosion or other techniques to clean the images
   C. Convex hull to identify the extents of the ball or droplets
   D. You could also do edge detection / blob detection instead of context hull
"""

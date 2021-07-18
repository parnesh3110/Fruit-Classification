# Fruit-Classification
//Import the following libraries before running the project:
from __future__ import division
import io
import os
import random
import cv2
import numpy as np
import time
from copy import deepcopy

The parameters for the HSV filter are predefined, you could change them according to your need but if you are just casually running the project it is recommended to not to do so.

Run the code, it will capture the photo of a fruit then it would classify the image into red, green, yellow image filter then would apply HSV and after calculating ripeness it would give output as Low, Medium, High Ripeness.

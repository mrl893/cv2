# cv2
n
import cv2
import numpy as np


img = cv2.imread('imgs.jpeg', -1)
# img = cv2.resize(img, (300, 300))
# img = cv2.resize(img, (0,0),  fx=0.3, fy=0.3)
# cv2.imshow('imgs', img)
# cv2.waitKey(0)
# cv2.destroyAllWindows()




print(img)
print(img.shape)

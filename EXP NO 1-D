import cv2
import numpy as np
import matplotlib.pyplot as plt
img = cv2.imread('/content/image cv4.jpeg')
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
kernel = np.ones((5,5), np.uint8)
dilated = cv2.dilate(gray, kernel, iterations=1)
plt.figure(figsize=(8,4))
plt.subplot(1,2,1)
plt.title("Original Image")
plt.imshow(gray, cmap='gray')
plt.axis('off')
plt.subplot(1,2,2)
plt.title("Dilated Image")
plt.imshow(dilated, cmap='gray')
plt.axis('off')
plt.show()

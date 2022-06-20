# SA-C-GENDER-CLASSIFIER
# Algorithm
1. Install the DeepFace library using the command pip install deepface
2. To Predict the gender of a person use this DeepFace library
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the image which we have imported. 
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable and print the prediction using this algorithm.

# Program:
## Program to implement 
## Developed by   : S.Sumyuktha Rani
## RegisterNumber :  212220230050

```
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('s1.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('m1.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:

![surya ss](https://user-images.githubusercontent.com/75235818/174488192-2dc22f05-150a-4834-acfb-daaff7dea9a1.png)

![sam ss](https://user-images.githubusercontent.com/75235818/174488221-471a4604-c2d5-497a-b042-d4a3ca9256d3.png)

# DEMO VIDEO YOUTUBE LINK:
[https://youtu.be/dgkx6u2lLR0](https://youtu.be/oP551PGB-JU)

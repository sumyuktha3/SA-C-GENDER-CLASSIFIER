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
![3](https://user-images.githubusercontent.com/75235032/173244294-7f727c3c-a1c5-4d09-ab77-73b6cd08dea1.jpg)

![4](https://user-images.githubusercontent.com/75235032/173244300-8fd32f1c-4d0a-48fc-9179-052e7a9c3ae7.jpg)


# DEMO VIDEO YOUTUBE LINK:
https://youtu.be/dgkx6u2lLR0

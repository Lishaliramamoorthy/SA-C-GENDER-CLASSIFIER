# SA-C-GENDER-CLASSIFIER
# Algorithm
1.To classify the gender of a person use the DeepFace library. <br>
2.DeepFace library is developed based on deep learning algorithms. <br>
3.Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements. <br>
4.Load and display the imported image. <br>
5.Pass the image to DeepFace library and analyze the image to predict gender of a person. <br>
6.This prediction is stored in result variable. <br>
7.Finally print the prediction using this algorithm. <br>


## Program:


# Program to implement 
## Developed by   :  Lishali.R
## RegisterNumber :  212220230028



## Output:
```

1. CODE :
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('bj.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('jungkook.jpg')
plt.imshow(img2[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])

```

![woman img](https://user-images.githubusercontent.com/75237886/174479263-1386e469-d62e-4e77-aadb-0c2b9a8935b4.png)

![woman](https://user-images.githubusercontent.com/75237886/174479276-8552c3d5-36e1-4c00-a11c-8dfbae71bc5c.png)

![man img](https://user-images.githubusercontent.com/75237886/174479296-c5b1d486-2bc8-43ac-b78b-18e12e940234.png)

![man](https://user-images.githubusercontent.com/75237886/174479302-ac9005c5-848b-4c06-8de7-109113768321.png)



2. DEMO VIDEO YOUTUBE LINK:

https://youtu.be/jFnJ_KYjbSU
 



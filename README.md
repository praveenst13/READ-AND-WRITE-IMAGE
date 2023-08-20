# READ AND WRITE AN IMAGE
## AIM
To write a python program using OpenCV to do the following image manipulations.
i) Read, display, and write an image.
ii) Access the rows and columns in an image.
iii) Cut and paste a small portion of the image.

## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Choose an image and save it as a filename.jpg
### Step2:
Use imread(filename, flags) to read the file.
### Step3:
Use imshow(window_name, image) to display the image.
### Step4:
Use imwrite(filename, image) to write the image.
### Step5:
End the program and close the output image windows.
## Program:
### Developed By:
### Register Number: 
i) #To Read,display the image
```
import cv2
image=cv2.imread("/home/swag/Downloads/images.jpg",1)
cv2.imshow("212222240077_praveen.s",image)
cv2.waitKey(0)


```
ii) #To write the image
```
import cv2
image=cv2.imread("/home/swag/Downloads/images.jpg",1)
w=cv2.imwrite('1.png',image)
cv2.imshow('212222240077_praveens',image)
cv2.waitKey(0) 


```
iii) #Find the shape of the Image
```python3

import cv2
import random
image=cv2.imread("/home/swag/Downloads/images.jpg",1)
print(image.shape)




```
iv) #To access rows and columns

```python3

import cv2
import random
image=cv2.imread("/home/swag/Downloads/images.jpg",1)

for i in range(100):
    for j in range(im.shape[1]):
        image[i][j]=[random.randint(0,255),random.randint(0,255),random.randint(0,255)]
cv2.imshow('212222230030_DHANUMALYA',color_img)
cv2.waitKey(0)

```
v) #To cut and paste portion of image
```python3

import cv2

image=cv2.imread("/home/swag/Downloads/images.jpg",1)

tag=image[750:802,933:985]
image[50:102,50:102]=tag
cv2.imshow('212222240077_Praveens',image)
cv2.waitKey(0)



```

## Output:

### i) Read and display the image

<br>
![dipt](https://github.com/praveenst13/READ-AND-WRITE-IMAGE/assets/118787793/40ef5827-fe45-403b-800f-397d8fcea305)
<br>


### ii)Write the image

<br>

![dipt2](https://github.com/praveenst13/READ-AND-WRITE-IMAGE/assets/118787793/286c2b29-d2fa-480b-a164-cb82360d415e)


<br>

### iii)Shape of the Image

<br>

![dipt3](https://github.com/praveenst13/READ-AND-WRITE-IMAGE/assets/118787793/5914e7fe-0ea1-4297-9ccb-cdc38904aede)


<br>

### iv)Access rows and columns
<br>
![dipt4](https://github.com/praveenst13/READ-AND-WRITE-IMAGE/assets/118787793/c0635403-f8f8-4750-afbf-e88c0509dc5e)


<br>
### v)Cut and paste portion of image
<br>

![dipt5](https://github.com/praveenst13/READ-AND-WRITE-IMAGE/assets/118787793/71488e4d-ad74-4a00-b7b4-52e80eb00990)



<br>

## Result:
Thus the images are read, displayed, and written successfully using the python program.

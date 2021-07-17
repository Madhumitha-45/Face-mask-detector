# Face-mask-detector
After the breakout of the worldwide pandemic COVID-19, there 
arises a severe need of protection mechanisms, face mask being the 
primary one. The basic aim of the project is to detect the presence 
of a face mask on human faces on live streaming video as well as 
on images. We have used deep learning to develop our face 
detector model. To create our face mask detector, we trained a two class model of people wearing masks and people not wearing 
masks. We fine-tuned MobileNetV2 on our mask/no mask dataset 
and obtained a classifier that is ~99% accurate. We then took this 
face mask classifier and applied it to real-time video streams by:
1. Detecting faces in video
2. Extracting each individual face
3. Applying our face mask classifier
Our face mask detector is accurate, and since we used the 
MobileNetV2 architecture. Experimental results show that our 
model performs well on the test data with 100% and 99% precision 
and recall, respectively.

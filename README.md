# UIRE-Net
The code of Paper "Vision-based Estimation of Worker Pose in Low-Light Conditions on Construction Sites".

The implementation is for non-commercial use only.

# Requirements
Python > 3.6

opencv

torchvision 0.2.1

# Test:

python test.py 

The script will process the images in the folders of "test" folder and the result will be in the "result" folder. 

(The training code will be given after the acceptance of the article)


Result:


![FIGSHOW](https://github.com/Chenxy875/UIRE-Net/assets/121841006/3a83e0ab-13dd-4c3f-98b0-40dda054b551)



You  can find the low-light construction dataset in google driven (It's coming!). 
Datasets:
![1691492902785](https://github.com/Chenxy875/UIRE-Net/assets/121841006/814bca86-2a37-4d35-8037-b50c47d0d545)

Backbone network:
![FIGPIP](https://github.com/Chenxy875/UIRE-Net/assets/121841006/5adb48cc-2887-4e12-a5f6-e2a98926a580)

Feature extraction:
![VGG16](https://github.com/Chenxy875/UIRE-Net/assets/121841006/c0c2df7d-e1da-4e02-a875-aebfa8de048b)

Ablation results:

![ablation](https://github.com/Chenxy875/UIRE-Net/assets/121841006/40466533-6a81-48f7-9f8d-e125b3b80f86)


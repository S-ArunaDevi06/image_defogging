# image_defogging

## Introduction
Fog is one of the major issus that makes driving dangerous in situations. In the era of developing autonomous vehicles, fog is a major concern as it will block the camera and the system will not be able to take appropriate decisions leading to accidents. To address this issue, this defogging system is developed.

## Dataset
The dataset that have been used for the development of this system is collected from Kaggle. It consists of more than 2000 images. The images are classified into two groups as light foggy and foggy and in various image formats: JPEG, JPG and PNG. Both foggy and light foggy images are put in a single set and used. The dataset can be accessed via https://drive.google.com/drive/folders/1KmYPEiqf5ZPxndrtoRTR-Ql1GRfnz7ik?usp=drive_link

## Proposed methodology
The proposed methodology for enhancing visibility and quality in foggy images leverages the Dark Channel Prior (DCP) method for defogging, followed by post-processing to improve clarity. Post-processing includes sharpening using laplacian kernel and brightening. 

## Result
Structural similarity index: 0.4954. The peak signal to noise ratio (psnr): 27.9056

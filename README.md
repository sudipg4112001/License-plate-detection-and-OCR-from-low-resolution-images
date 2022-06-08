# LPR-LRtoHR-OCR
![Python](https://img.shields.io/badge/Python%20-Python%203.9.1-yellowgreen?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas%20-blue?style=for-the-badge&logo=Pandas)
![Numpy](https://img.shields.io/badge/Numpy%20-violet?style=for-the-badge&logo=Numpy)
![OpenCV](https://img.shields.io/badge/OpenCV%20-important?style=for-the-badge&logo=OpenCV)
![Real esrGAN](https://img.shields.io/badge/RealesrGAN%20-green?style=for-the-badge&logo=RealesrGAN)
![pytesseract](https://img.shields.io/badge/pytesseract%20-seagreen?style=for-the-badge&logo=pytesseract)
## Aim:
- Detection on vehicle license plate from low resolution traffic images.(Using yoloV5)
- Extraction of license plates from the images and zoom them 5x times. (Using openCV)
- Enhance the resolution of the extracted images. (Using Real esrGAN)
- Extract the license plate text. (Using pytesseract)

## Dependencies:
- pandas
- numpy
- yoloV5
- openCV
- esrGAN
- pytesseract

## Workflow diagram
![Flowchart ](https://user-images.githubusercontent.com/60208804/171845227-5cfc6d17-29fe-4317-a209-3fa4a52cdbb5.jpg)

# License plate detection output
![image](https://user-images.githubusercontent.com/60208804/171849092-8f23c1b0-ba02-4290-9601-2d0f6d8a8835.png)

# Extraction of license plate
![image](https://user-images.githubusercontent.com/60208804/171849223-a26b5a37-a43c-48c2-8dda-992f0a36bee9.png)

# Low resolution output after zooming
![image](https://user-images.githubusercontent.com/60208804/171849294-528a9f85-4de9-4003-8425-c926735a7593.png)

# Low resolution to High resoltution
![image](https://user-images.githubusercontent.com/60208804/171849379-00581006-a1f5-4c50-aaed-59172ef0a675.png)

# Text extraction from license plate
![image](https://user-images.githubusercontent.com/60208804/171849634-7a24ba13-ed97-4121-b1b9-eecb7f3ec55a.png)

# Model Performance
- Mean Average Precision(mAP)=92.6%
- Precision=94.8%
- Recall=87.8%

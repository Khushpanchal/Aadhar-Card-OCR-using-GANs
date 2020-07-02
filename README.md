# Aadhar-Card-OCR-using-GANs

Project:- https://drive.google.com/drive/folders/1HEwF2cj0jZwQ0MuKVMi-jMCTEV4tg28Q?usp=sharing

Reference:- https://github.com/idealo/image-super-resolution

Process Used:- Described in the given file using comments (OCR.ipynb)
Pretrained Model:- Using ISR module in Python which is trained on DIV2K dataset.
Run the code in Google Colab with GPU runtime

General Process:-
1. Taken the low quality aadhar image use ISR module to get high quality aadhar image.
2. Put the image into tessereact to extract aadhar no.
3. If aadhar no. not found sharpen the image and then again send it into tesseract.
4. if not found again then rotate the image by 90 degree and repeat the process.
5. After find aadhar no. validate it using Verhoeff Algorithm

Note:- Before converting the image into high quality do the OCR with low qualty images.

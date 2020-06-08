# Aadhar-Card-OCR-using-GANs

COLAB link of project:- https://colab.research.google.com/drive/1qlGPwWpyi93Q7b_9nEPCgmEU2eBa0i9V?usp=sharing

Process Used:- Described in the given file using comments
Pretrained Model:- https://drive.google.com/file/d/1YKpJbosFgdpLK17nShIpYvyMn2yY5rpE/view?usp=sharing
Github repository containing the GAN code: https://github.com/xinntao/ESRGAN.git
Run the code in Google Colab with GPU runtime

General Process:-
1. Taken the low quality aadhar image put it into pretrained GAN model to get high quality aadhar image.
2. Put the image into tessereact to extract aadhar no.
3. If aadhar no. not found sharpen the image and then again send it into tesseract.
4. if not found again then rotate the image by 90 degree and repeat the process.
5. After find aadhar no. validate it using Verhoeff Algorithm

Things left:-
1. GAN model was trained on general coloured image dataset, so we need to train it on text images dataset.
2. Masking of Aadhar Caard No.

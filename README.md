# FaceGAN - Deep Convolutional Generative Adversarial Network for Face Generation
The objective of this project is to develop a Deep Convolutional Generative Adversarial Network (DCGAN) that can generate realistic human faces. The implementation is done using the Pytorch framework, and the model is trained on the [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset, which consists of over 200,000 celebrity faces with varying poses and facial expressions.
<p class="row" float="left" align="middle">
<img style="width: 100%; height: auto;" src="assets/generated_faces.gif"/>
</p>

## DCGAN
DCGAN stands for Deep Convolutional Generative Adversarial Network, it's a type of Generative Adversarial Network (GAN) used for generating new data samples with similar characteristics as the training data. It uses deep convolutional neural networks in both the generator and discriminator parts of the GAN architecture. The generator generates new samples, while the discriminator evaluates the authenticity of the generated samples by trying to distinguish them from the real training data. The two parts compete against each other, with the generator trying to produce more convincing samples, and the discriminator trying to better distinguish the fake from the real. This results in the generator gradually learning to generate more and more realistic samples. DCGANs are commonly used for generating images, videos, and audio.

The CelebA dataset is preprocessed and resized to 64x64 pixels to fit the input size of the DCGAN. The generator network is designed to take a random noise vector as input and generate a new image. The discriminator network takes an image as input and outputs a probability score indicating whether the image is real or generated. The model is trained using the binary cross-entropy loss function to optimize the generator and discriminator networks.

The performance of the model will be evaluated by generating a set of new images and visually inspecting the quality of the generated faces. The quality of the generated faces will be assessed based on their visual realism, diversity, and level of detail.

Overall, the project aims to demonstrate the power of deep learning models in generating realistic images of human faces and provide a practical example of how to implement a DCGAN using Pytorch.

## Results
The following images show the results of the DCGAN after training for 10 epochs on the CelebA dataset.
<p class="row" float="left" align="middle">
<img style="width: 75%; height: auto;" src="assets/results.png"/>
</p>

The following images are some of my favorite generated samples:
<p class="row" float="left" align="middle">
<img src="samples/epoch4_2448.jpg"/>
<img  src="samples/epoch6_2898.jpg"/>
<img  src="samples/epoch7_2975.jpg"/>
<img  src="samples/epoch7_3408.jpg"/>
<img  src="samples/epoch7_3741.jpg"/>
<img  src="samples/epoch7_7773.jpg"/>
<img  src="samples/epoch9_6237.jpg"/>
<img  src="samples/epoch10_135.jpg"/>
<img  src="samples/epoch10_3128.jpg"/>
<img  src="samples/epoch10_5197.jpg"/>
<img  src="samples/epoch5_2557.jpg"/>
<img  src="samples/epoch10_5622.jpg"/>
<img  src="samples/epoch10_7262.jpg"/>
<img  src="samples/epoch10_7640.jpg"/>
<img  src="samples/epoch10_8631.jpg"/>
<img  src="samples/epoch10_9065.jpg"/>
<img  src="samples/epoch10_9226.jpg"/>
<img  src="samples/epoch10_9257.jpg"/>
<img  src="samples/epoch10_9449.jpg"/>
<img  src="samples/epoch10_9534.jpg"/>
<img  src="samples/epoch10_9625.jpg"/>
<img  src="samples/epoch9_1863.jpg"/>
<img  src="samples/epoch10_5621.jpg"/>
<img  src="samples/epoch7_6601.jpg"/>
</p>

## Requirements
The following hardware and software were used for training the model:
- GPU: Apple M1 Max 32-Core-GPU
- CPU: Apple M1‌ Max 10-core CPU
- RAM: 32GB SSD
- Operating System: macOS Ventura 13.1
- Python version: 3.9.15
- PyTorch version: PyTorch-Nightly 2.0.0.dev20221222

  
## Contributing
Contributions are welcome! :heart: Please open a pull request or issue for any improvements or bug fixes.

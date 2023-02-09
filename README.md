# Human-Face-Generator-DCGAN
A Deep Convolutional Generative Adversarial Network (DCGAN) that generates human faces. This project is implemented using PyTorch and trained on the [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset.
<p class="row" float="left" align="middle">
<img style="width: 100%; height: auto;" src="generated_faces.gif"/>
</p>

## DCGAN
DCGAN stands for Deep Convolutional Generative Adversarial Network, it's a type of Generative Adversarial Network (GAN) used for generating new data samples with similar characteristics as the training data. It uses deep convolutional neural networks in both the generator and discriminator parts of the GAN architecture. The generator generates new samples, while the discriminator evaluates the authenticity of the generated samples by trying to distinguish them from the real training data. The two parts compete against each other, with the generator trying to produce more convincing samples, and the discriminator trying to better distinguish the fake from the real. This results in the generator gradually learning to generate more and more realistic samples. DCGANs are commonly used for generating images, videos, and audio.

## Results
The following images show the results of the DCGAN after training for 10 epochs on the CelebA dataset.

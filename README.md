# VQ-VAE
Implementation of paper: Neural Discrete Representation Learning (VQ-VAE)
</br >
Original Paper: https://arxiv.org/pdf/1711.00937.pdf
</br ></br >
Note: This implementation is done only on CIFAR-10 dataset.
</br ></br >
VQ-VAE.ipynb file contains the training and inference of VQVAE model along with the training and inference of pixelCNN model trained on top of discrete latents produced in previous step.
</br ></br >
To train the pixelcnn model, first VQVAE model has to be trained. We are using pretrained model weights of VQVAE model which is also provided in this repository as 'vqvae_25000.pth' file.
</br ></br >
If only need to produce the outputs, the pretrained weights are given (refer the given notebook file for visualizing). Also if need to produce the random outputs using pixelcnn 
prior, again weights are given "vqvae_pixelcnn_prior_65.pth" (refer the given notebook file for visualizing).
</br ></br >
Reconstruction of images using VQVAE model.
</br >

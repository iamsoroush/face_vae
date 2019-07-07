# Deep Facial Atrribute Manipulation
Implementation of Variational Auto-Encoder (VAE) and Deep Feature Consistent VAE for facial attribute manipulation using Keras and Tensorflow-dataset module.

Source paper: [Deep Feature Consistent Variational Autoencoder](https://arxiv.org/abs/1610.00291)

Try it yourself: open **face_vae.ipynb** in a Google colab notebook and run cells one-by-one.


# Results
## Plian VAE: reconstruction
![alt text](https://github.com/iamsoroush/face_vae/blob/master/download.png)


## DFC-VAE with loss defined on early layers of pre-trained VGG19: reconstruction
![alt text](https://github.com/iamsoroush/face_vae/blob/master/download%20(2).png)


## DFC-VAE with loss defined on intermediate layers of pre-trained VGG19: reconstruction
![alt text](https://github.com/iamsoroush/face_vae/blob/master/download%20(1).png)


## Facial Attribute Manipulation: Adding *Smile* to faces
![alt text](https://github.com/iamsoroush/face_vae/blob/master/download%20(3).png)

## Facial Attribute Manipulation: Removing *Smile* from faces
![alt text](https://github.com/iamsoroush/face_vae/blob/master/download%20(4).png)

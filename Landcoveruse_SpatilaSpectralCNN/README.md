Paper overview:
The authors propose a very interesting method for landcover classification based on 1D CNN and 2D CNN. They used features extracted from both Spatial and Spectral values of each pixel:

- Spectral : the values of pixel in each spectral band (channel) of the multispectral remote sensing image.
- Spatial: the values of the pixels surrounding the current pixel (pixel of interest centred patches) in all spectral bands (channels)

What we are trying to implement:

![alt text](image.png)

Paper link:

https://www.researchgate.net/publication/317053979_Learning_and_Transferring_Deep_Joint_Spectral-Spatial_Features_for_Hyperspectral_Classification

Data Link:

https://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes

Now working on:

Finding out what is wrong with the loss !

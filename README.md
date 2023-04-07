# Anime Faces Generation <br>
* Generate anime faces at the resolution of 128px, code is available at **AnimeFaces_generation_128px.ipynb**. <br>
* The Frechet Inception Distance (FID) calculated from 50000 generated images using the official implementation of FID to Pytorch is **6.94**. <br>
* Selected generated images: <br><br>
![128px](generated%20images/128px.png)

## Interpolation <br>
* Interpolation of latent space, code is available at
* Image 1 &#8594; Image 2 <br>
![Interpolation1](generated%20images/Interpolation1.png) <br>
* Image 2 &#8594; Image 3 <br>
![Interpolation2](generated%20images/Interpolation2.png) <br>
* Image 3 &#8594; Image 1 <br>
![Interpolation3](generated%20images/Interpolation3.png) <br>
* Image 1 &#8594; Image 2 &#8594; Image 3 &#8594; Image 1 <br>
![Interpolation3](generated%20images/Interpolation.gif) <br>

## References <br>
<a id="1">[1]</a> Tero Karras, Timo Aila, Samuli Laine, Jaakko Lehtinen. Progressive Growing of GANs for Improved Quality, Stability, and Variation. https://arxiv.org/abs/1710.10196 <br>
<a id="2">[2]</a> Lars Mescheder, Andreas Geiger, Sebastian Nowozin. Which Training Methods for GANs do actually Converge? https://arxiv.org/abs/1801.04406 <br>
<a id="3">[3]</a> Github repository: https://github.com/aladdinpersson/Machine-Learning-Collection/tree/master/ML/Pytorch/GANs/ProGAN <br>
<a id="4">[4]</a> Github repository: https://github.com/GaParmar/clean-fid <br>
<a id="5">[5]</a> Github repository: https://github.com/mseitzer/pytorch-fid <br>
<a id="6">[6]</a> Kaggle notebook: https://www.kaggle.com/code/theoviel/conditional-progan-30-public <br>


# wgan-project-ECE5995
Understanding and Comparing WGAN and WGAN-GP Implementations


## Running the GAN notebooks
No changes necessary to run VanillaGAN.ipynb. One issue with this notebook is that I could not get the GAN to run on a GPU so it runs on CPUs only. This means quite long training times (close to 8 hours on colab). This would likely be better run locally or altered for GPU acceleration.

To run WGAN_WGAN-GP_Comparison.ipynb, be sure to update the GAN type in the "args" array to WGAN or WGAN_GP and use the corresponding "gan" model definition line, depending on the model you wish to train. Also update the image printing lines with the appropriate GAN type name to correctly print images. 

## Regarding definitions and helper functions
All required functions are defined above the arg setup and training code block. The generator and discriminator each have their own code block and there's another for utility functions. Be sure to run each of these code blocks, as well as the initial imports and data code block before attempting to train a GAN model or print images. 

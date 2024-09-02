# README



* **First of all, you can find the dataset on Kaggle:**

  * **Dataset  => https://www.kaggle.com/kwentar/blur-dataset.**


## Steps to Execute

* I have not used the blurred images that are given in the original dataset for image deblurring. They are spatially variant due to motion blurring and defocus-blurring. I have added Gaussian blurring to the images using the `add_guassian_blur.py` script inside the `src` folder. Then I have used these images for deblurring.
* **The following is the order of execution:**
  1. `add_gaussian_blur.py`
  2. `deblur_ae.py`
* ***Note: Execute all the scripts while being within the `src` folder inside the terminal***.



## <u>Some Results</u>



* **Blurred Image**

  ![](https://github.com/Ps20928/image-debluring-using-ML/blob/main/test_data/gaussian_blurred/image_1.jpg?raw=true)

  **Final Deblurred Image**

  ![](https://github.com/Ps20928/image-debluring-using-ML/blob/main/test_data/image_1.jpg?raw=true)


## <u>References</u>

* Paper: Image Deblurring with BlurredNoisy Image Pairs, **Lu Yuan, Jian Sun, Long Quan, Heung-Yeung Shum.**
* [Image super-resolution as sparse representation of raw image patches](https://www.researchgate.net/publication/221364186_Image_super-resolution_as_sparse_representation_of_raw_image_patches), **Jianchao Yang†, John Wright‡, Yi Ma‡, Thomas Huang†**.
* mage Deblurring and Super-Resolution Using Deep Convolutional Neural Networks](https://www.researchgate.net/publication/328985265_Image_Deblurring_and_Super-Resolution_Using_Deep_Convolutional_Neural_Networks), **Fatma Albluwi, Vladimir A. Krylov & Rozenn Dahyot**.
  * [GitHub Code](https://github.com/YapengTian/SRCNN-Keras).

# **Chest X-Ray Denoising Project**

Welcome to the **Chest X-Ray Denoising Project** repository! This is a hands-on resource for researchers, developers, and enthusiasts who are interested in exploring techniques to improve the quality of noisy chest X-ray images. By leveraging state-of-the-art image denoising methods, you can make diagnostic processes more reliable and effective.

---

## **Overview**

This repository provides:

- A **noise generation function** (simulating 90% dose reduction) to create noisy chest X-ray images.
- Functions to calculate key **evaluation metrics** to measure the effectiveness of your denoising techniques.
- Sample X-ray images (from [Stanford's Public Repository](https://stanfordmlgroup.github.io/competitions/chexpert/)) to get you started.
- Example output showcasing how our denoising pipeline performs with the provided noisy samples.

### **The Goal**
Take the sample images, add noise using the provided function, apply your denoising algorithm, and evaluate the results using the included metrics. Compare your output against the original clean image to measure performance.
I am including my best results on this repo as well.

---

## **Features**

- 🌟 **Simulate Noisy Images**: Use our `create_noise` function to replicate real-world scenarios of dose-reduced X-rays (90% reduction).
- 📏 **Evaluate Your Results**: Included metrics like **PSNR** (Peak Signal-to-Noise Ratio) and **SSIM** (Structural Similarity Index) help you quantify the quality of your denoised images.
- 📷 **Sample Outputs**: See what denoising looks like in action with our included output examples.
- 🚀 **Get Started Quickly**: Preloaded data and simple-to-follow scripts make it easy to dive in and test your own denoising algorithms.
# **Sample output, more in the main directory, use Jupyter Notebook template to emulate**
![sample processed image](5_combined.png)


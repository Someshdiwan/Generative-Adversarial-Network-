# Generative Adversarial Networks (GAN) Implementations

Welcome to the **Generative Adversarial Networks (GAN)** repository! This repository features a variety of GAN architectures and experiments, showcasing their potential in tasks like image generation, domain translation, and high-resolution image synthesis. Explore implementations of **DCGAN**, **CycleGAN**, **Pix2Pix**, **Progressive Growing GAN**, and more.

![Deep Fake GAN gif](https://i.makeagif.com/media/5-23-2023/BepLC8.gif)

<img src="https://drive.google.com/uc?export=view&id=1p77tW24POFHn4QjD6hJKCA26rwqGuJi7" alt="DCGAN Results" width="400" />

<img src="https://drive.google.com/uc?export=view&id=1VTOAH7LzgPIhbD8xxWr93QV_UQd0PYwH" alt="CycleGAN Example" width="400" />

<img src="https://drive.google.com/uc?export=view&id=1AhtsJpdTWTp13vWHj2Sis_uKfGhgbDI6" alt="Basic GAN Output" width="400" />

<img src="https://drive.google.com/uc?export=view&id=1swz63bKGQekGltW5sM38mubc6T34xaxN" alt="Pix2Pix Translation" width="400" />

<img src="https://drive.google.com/uc?export=view&id=1VTOAH7LzgPIhbD8xxWr93QV_UQd0PYwH" alt="<DESCRIPTIVE_TEXT>" width="400" height="auto" />
## 🚀 About

Generative Adversarial Networks (GANs) are a groundbreaking class of machine learning models. A GAN consists of two networks:

- **Generator**: Creates synthetic data that mimics real data.
- **Discriminator**: Differentiates between real and generated data.

These two networks are trained in a zero-sum game, pushing the Generator to produce increasingly realistic outputs. GANs have applications in:

- **Image Synthesis**: Generating high-quality, photorealistic images.
- **Image-to-Image Translation**: Transforming images from one domain to another.
- **Unpaired Domain Adaptation**: Learning mappings between datasets without direct pairings.
- **Progressive Learning**: Generating high-resolution images via stepwise training.
  


## 📂 Repository Structure

```plaintext
Generative-Adversarial-Network/
├── Basic_GAN.ipynb                     # Basic GAN implementation
├── Conditional_GAN.ipynb               # Conditional GAN implementation
├── CycleGAN for Unpaired Image Translation.ipynb  # CycleGAN implementation
├── Deep_Convolutional_GAN.ipynb        # DCGAN implementation
├── Pix2Pix for Paired Image Translation.ipynb     # Pix2Pix implementation
├── Progressive Growing GAN.ipynb       # Progressive GAN for high-res image data
├── README.md                           # Repository documentation
```
```
🔧 Features

Basic GAN: Demonstrates the fundamental GAN concept with a simple generator and discriminator.
Deep Convolutional GAN (DCGAN): Uses convolutional layers for stable, high-quality image generation.
Conditional GAN (cGAN): Generates data conditioned on additional information like class labels.
CycleGAN: Performs unpaired image-to-image translation tasks, e.g., converting horses to zebras.
Pix2Pix: Executes paired image-to-image translation, e.g., transforming sketches to photos.
Progressive Growing GAN: Produces high-resolution images by progressively increasing model complexity.
Visual Demonstrations
```
```
🌟 Highlights

GAN Architectures:

Basic GAN: Introduces the core GAN framework.
DCGAN: Employs deep convolutional networks for generating photorealistic images.
Conditional GAN: Adds control over the generation process through input conditions.
CycleGAN: Enables translation between two unpaired datasets.
Pix2Pix: Translates between two paired datasets with pixel-level mappings.
Progressive GAN: Scales GANs to synthesize high-resolution images.

```
GAN Output:

Progressive Growing GAN Results
<img src="https://drive.google.com/uc?export=view&id=1XbxR2I_Eh-ne_CvPeKjKeBBjXvZbnPlL" alt="Progressive GAN Output" width="400" />

---
🛠️ Technologies Used

Python 3.x
TensorFlow / PyTorch
NumPy
Matplotlib
OpenCV
PIL (Python Imaging Library)
---

📊 Getting Started

Clone the repository:

git clone https://github.com/Someshdiwan/Generative-Adversarial-Network.git
cd Generative-Adversarial-Network

Install the required Python libraries:
pip install

Explore and execute the Jupyter notebooks to experience the power of GANs.

---

---

📚 Resources

Tutorials and Research Papers:

Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks: https://junyanz.github.io/CycleGAN/

Style based GAN: https://www.naukri.com/code360/library/style-based-gan

Original GAN Paper / Generative Adversarial Nets (Goodfellow et al., 2014): https://arxiv.org/abs/1406.2661

Progressive Growing of GANs: https://arxiv.org/abs/1710.10196

---

```
🤝 Contributions
We welcome your contributions to enhance this repository! 

You can: Report issues or suggest features.

Fork the repository, make improvements, and submit a pull request.

🌟 Support
If you find this repository helpful, please consider giving it a ⭐ on GitHub to show your support!
```

# GAN-space-objects

Генерация космических объектов с помощью генеративно-состязательных сетей (GAN)

Датасет собран через: https://deep-fold.itch.io/pixel-planet-generator

![real objects](images\real.png "real objects")
### DCGAN
![dcgan generated](images\dcgan.png "dcgan generated")

### Self-Attention-GAN

![self-attention-gan generated](images\self-attention-gan.png "self-attention-gan generated")

### Sin-GAN
В отличие от классических GAN, Sin-GAN обучается на одном изображении и может использоваться для решения задач гармонизации, анимации, редактирования изображения. Более подробно тут https://arxiv.org/pdf/1905.01164. 

В данном примере модель использовалась для генерации gif анимации.

<img src="images/black_hole_1.gif" alt="scale-0-alpha-0.15-beta-0.95" loop=infinite>
<img src="images/black_hole_2.gif" alt="scale-1-alpha-0.05-beta-0.75" loop=infinite>
<img src="images/black_hole_3.gif" alt="scale-1-alpha-0.15-beta-0.7" loop=infinite>

<img src="images/galaxy_1.gif" alt="scale-1-alpha-0.1-beta-0.6" loop=infinite>
<img src="images/galaxy_2.gif" alt="scale-2-alpha-0.1-beta-0.75" loop=infinite>
<img src="images/galaxy_3.gif" alt="scale-4-alpha-0.1-beta-0.65" loop=infinite>

<img src="images/earth_1.gif" alt="scale-0-alpha-0.45-beta-0.5" loop=infinite>
<img src="images/earth_2.gif" alt="scale-0-alpha-0.5-beta-0.65" loop=infinite>
<img src="images/earth_3.gif" alt="scale-1-alpha-0.05-beta-0.5" loop=infinite>

### StyleGAN
todo
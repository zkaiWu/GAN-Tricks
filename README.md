# GAN-Tricks


> GAN tricks list and where they come from 

| No   | Description  | Paper for short | Paper link| 
|  ----  | ----  |  ----  | ----  |
| 1  |   Swap the camera pose when using camera pose as condition in generator, using just when update generator  | eg3d | [https://nvlabs.github.io/eg3d/](https://nvlabs.github.io/eg3d/) |
| 2  |  blur images as they enter the discriminator, gradually reducing the blur amount over the first 200K images| eg3d (supp)  | [https://nvlabs.github.io/eg3d/](https://nvlabs.github.io/eg3d/) |
| 3  |  Two stage training, 64 -> 256 resolution for first stage, 128 -> 512 resolution for second stage or anneal increase the resolution| eg3d (supp)  | [https://nvlabs.github.io/eg3d/](https://nvlabs.github.io/eg3d/) |
| 4  |Density regularization| eg3d (supp)  | [https://nvlabs.github.io/eg3d/](https://nvlabs.github.io/eg3d/) |
| 5  |No use for increasing batch size| 3dgp (3D ImageNet Generation)| [https://snap-research.github.io/3dgp/](https://snap-research.github.io/3dgp/) |
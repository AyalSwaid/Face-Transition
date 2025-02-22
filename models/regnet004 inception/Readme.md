# Regnet004 inception Reconstruction

### Note: loss scale is different from other models (because of different normalizationa dn tricks)
## Details
* val_loss=0.083, train_loss_epoch=0.078
* encoder is pretrained regnety004 model and decoder is a sequence of transposed convolutions and google inception blocks
* loss function: MSE
* trained on ffhq128_70k
* input/output shape: (3,128,128), latent shape: (440,4,4), x2 smaller than hp_v5 model
## Learning Curve:
![learning curve](https://github.com/user-attachments/assets/a1cee2b2-05ba-43a6-9f98-b83436d200ab)


## Some images reconstructions
![1](https://github.com/user-attachments/assets/7b60ae03-0e81-4eb2-a077-c3938239c771)


![2](https://github.com/user-attachments/assets/c6b0019c-b176-414e-b2ef-895f69899103)

![3](https://github.com/user-attachments/assets/e7780743-3254-482f-b298-a0ee4591f5da)

![4](https://github.com/user-attachments/assets/155cd5ab-16f8-47be-ad0c-4fe3799a0447)

![5](https://github.com/user-attachments/assets/a6ae9490-c0fb-450c-ae0b-2fec108c7026)

![6](https://github.com/user-attachments/assets/ca3c0ebd-0b1c-480c-b8fa-f4f20222ea92)

![7](https://github.com/user-attachments/assets/be296eff-b050-45bd-9b4c-fb405305188d)


![8](https://github.com/user-attachments/assets/71517e9e-0b6b-4503-ac8b-5376b77b49b0)

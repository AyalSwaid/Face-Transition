# Face-Transition
Built VAE that reconstruct human faces (model parameters and pickle files attached), then, given two human faces A and B do transition from face A to face B smoothly by interpolating their latent codes.

# Examples

![ezgif-1a195e67bf273b](https://github.com/user-attachments/assets/a745e280-fa6f-4f87-b3cd-f460e9084f6c)

![ezgif-1c53119a5c777d](https://github.com/user-attachments/assets/b108f5b5-a96b-422b-807e-287c5573b7ea)

# Models
### found under models folder
1. VAE512 - VAE built using standard Convolutions and Transposed Convolutions. Latent shape: (512,)
2. regnet004 inception - standard AE (not VAE) its encoder is a regnet004 pretrained model, and the decoder is a sequence of transposed convolutions and google inception blocks. Latent shape (440, 4, 4)
3. hp_v5 - standard AE (not VAE) - best reconstruction result but the largest model , encoder is a regnet016 pretrained model and decoder is a custom CNN network. Latent shape (888, 4, 4)

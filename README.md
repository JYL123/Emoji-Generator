# Emoji-Generator

A generative adversarial networks (GANs) is built to digest training data of emojis and output new emojis that's not been seen before (not in the training data). The GAN model is built with a generator and a discriminator.

The generator is used to learn to generate emojis. The discriminator learns to distinguish the output of the generator from real data, and penalize the generator for producting bad results.

The model is referenced from [Radford et al., 2015](https://arxiv.org/abs/1511.06434) and the picture is as below: 
![alt text](https://github.com/JYL123/Emoji-Generator/blob/main/pics/Gan-Architecture.png)


Several selected newly generated emojis are shown below:

<p float="left">
  <img src="/selectedOuput/generated/girl_generated.jpeg" width="100" />
  <img src="/selectedOuput/generated/happy_face_generated.jpeg" width="100" /> 
  <img src="/selectedOuput/generated/sad_face_generated.png" width="100" />
  <img src="/selectedOuput/generated/very_sad_face_generated.jpeg" width="100" />
</p>

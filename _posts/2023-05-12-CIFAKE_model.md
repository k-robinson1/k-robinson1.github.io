# CIFAKE Model Complete!
# CIFAKE Model Complete!

I designed a model that can distinguish between real and AI-generated images using the CIFAKE dataset. The architecture I used was EfficientNetB0 and was able to achieve an accuracy of 97.94% which is higher than any other models I could find on the internet.

Here are some of the architectures I tried:
|   Technique  |     Result     | 
|:-------------|:--------------:|
| Resnet18     |    97.14%      |   
|EfficientNetB0|    97.95%      | 
| Convnext_tiny|    97.39%      |   

I also tried varying both the learning rate and weight decay value but found that the default values of 0.001 and 0.01 respectively remained optimal. I also tried implementing data augmentation but this actually reduced the validation accuracy since it must have interfered with the unique differences between AI generated images and real images.


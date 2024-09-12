# AdverserialPatches

This repository demonstrates the concept of adversarial patches in deep learning. Adversarial patches are small images designed to fool image recognition models into misclassifying images. By strategically manipulating the pixels within the patch, we can force a model to predict a chosen target class, even when the patch is placed on different images.

This specific example uses a pretrained ResNet34 model and the TinyImageNet dataset. It trains a grayscale patch that, when added to an image, tricks the model into predicting the target class "volcano". The code includes functions for training the patch, evaluating its effectiveness, and visualizing the generated patch. It also shows examples of how the patch can be applied to different images to alter their classification.

This demonstration provides a practical illustration of how adversarial patches can be created and used to manipulate the predictions of deep learning models.

## Performance of pretrained ResNet34 without adverserial patch
![image](https://github.com/user-attachments/assets/a9c48f30-c4c2-4e77-88e4-714d621caf95)


## Performance of pretrained ResNet34 with adverserial patch designed to reclasify image to a volcano
![image](https://github.com/user-attachments/assets/393cbe25-845c-4600-9dfb-a289bd0fb949)

## Patch deployed in real world
![image](https://github.com/user-attachments/assets/d12a548c-196c-4e8f-bad5-bbd6081014f1)


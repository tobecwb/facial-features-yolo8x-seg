## YOLOx8 model segmentation for face features

Segment the following class:

- eye
- eyebrown
- nose
- mouth

![woman_sample](https://raw.githubusercontent.com/tobecwb/facial-features-yolo8x-seg/main/woman_sample.jpg)
--- 

Segmentation model specially made to generate image masks for manual editing of images from https://github.com/tobecwb/stable-diffusion-regularization-images

The training was done only with female faces, but initial tests showed that it works reasonably well with male faces too.
![man_sample](https://raw.githubusercontent.com/tobecwb/facial-features-yolo8x-seg/main/man_sample.jpg)

For better results, it is interesting to train with images of a male face too (I will do this in the future).

The images used to train this model were 100 images of women taken from https://github.com/tobecwb/stable-diffusion-regularization-images, (resolution 1024px).

Dataset annotations made with Roboflow:
https://app.roboflow.com/tobe81cwb/facial-features-2ydjv/overview

Training through Ultralytics HUB:
https://hub.ultralytics.com/models/JqoT0o5pwOOYxX0wbHT7

Images from:
https://github.com/tobecwb/stable-diffusion-regularization-images

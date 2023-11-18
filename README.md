## YOLOx8 model segmentation to face features

Segment the following features (class):

- eye
- eyebrown
- nose
- mouth

--- 

Segmentation model specially made to generate image masks for manual editing of images from https://github.com/tobecwb/stable-diffusion-regularization-images

The training was done only with female faces, but initial tests showed that it works reasonably well with male faces too.

For better results, it is interesting to train with images of a male face too (I will do this in the future).

The images used to train this model were 100 images of women taken from https://github.com/tobecwb/stable-diffusion-regularization-images, (resolution 1024px).

Dataset annotations made with Roboflow:
https://app.roboflow.com/tobe81cwb/facial-features-2ydjv/overview

Training through Ultralytics HUB:
https://hub.ultralytics.com/models/JqoT0o5pwOOYxX0wbHT7

Images from:
https://github.com/tobecwb/stable-diffusion-regularization-images

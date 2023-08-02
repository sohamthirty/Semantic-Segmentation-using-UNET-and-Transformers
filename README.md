# Semantic-Segmentation-using-UNET-and-Transformers

## Data
**[Cityscapes Dataset | Semantic Understanding of Urban Street Scenes](https://www.cityscapes-dataset.com/)**

- • Cityscapes has been widely used as a benchmark dataset for evaluating and developing computer vision algorithms related to urban scene analysis, semantic segmentation, object detection, and more. It consists of high-resolution images captured from the driver's perspective in various cities, including street scenes, buildings, pedestrians, vehicles, and other urban elements.

- • The dataset provides pixel-level annotations, such as semantic segmentation, instance segmentation, and fine-grained object annotations, to enable detailed analysis of urban scenes. 

## Preprocessing
- • 256x256px images with 31 semantic classes were splitted into Training-Test-Validation as 2975-300-200.
- • Resize all the images, normalize the input image and create black mask of the same size as target/
- • Map the color to class for each pixel of the target image by matching the given class id.

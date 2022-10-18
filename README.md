<img style="float: right;" src="README/DWE_logo.avif">

# Underwater Object Detection Project

## Project Overview
This project will work on developing a smooth pipeline for developing an underwater object detection model. This will include a standardized and documented process for labeling data, segmenting training/test data, training a model, and testing robustness of models.

Document all of the standardizations and processes in the folder labelled: `Standard_Practices`

The actual model will be a YOLOv5 machine learning model that will be used to detect an arbitrary object/entity that is underwater. 

Entities will be classified to the best of the model's ability and then any unclassified objects would be "remembered" to create new training datasets.

Ideally, unclassified objects would be grouped based on similarity and therefore make it east to be labelled by humans.

## Languages, Tools, and Frameworks
- Python 3.7+
- OpenCV
- Numpy
- PyTorch
- *CVat.org?*
 
## Style Guide
Follow the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) for writing clean Python code.

Also utilize an automated linting tool that is required to be used before pushing code to a feature branch.

All code will be developed on feature branches and pull requests must be submitted and approved in order to be merged into the main branch.

Squash all commits in a feature branch to a single commit before creating/merging pull requests. You could utilize `git rebase -i` for example.

## Sample Datasets
- https://github.com/xinzhichao/underwater_datasets
- https://drive.google.com/drive/u/1/folders/1s6ydO1pjPwJe1my90xJJD1LyrQWlst6i
- https://drive.google.com/drive/folders/13KApjGaWNkoPvErFOBmrsNx6ebCpH_IV
- https://drive.google.com/drive/folders/1GQGi8lUYJh9b7z8Vytbuw29p9ZR7L-31

## Other Resources
- Utilize pre-processing techniques for input data to improve model
- Use data augmentation practices to create larger training sets from smaller ones
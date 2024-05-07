# GitHub repository for Software Development Project, Joe Holloway, 21016724

> EXPLORING COMPUTER VISION AND ITS POSSIBLE IMPLEMENTATION FOR LIVE POSITIONAL GRAPHICS IN HORSE RACING

## Outline of code within this project:

1. `Horse-Racing-2` -- This folder contains an annotated dataset of horse racing images used for the training of a computer vision model. The images are split into the following proportions: 70% for training, 10% for validation and 20% for testing.
2. `PyTorch_learning_files` -- This folder contains all the files, scripts and notebooks used, adapted and created while learning the fundamentals of machine learning and PyTorch. These files correspond to Daniel Bourke's "Zero to Mastery Learn PyTorch for Deep Learning" course that can be found [here](https://www.learnpytorch.io/). It should be noted that these files have not been formatted or documented extensively for viewing.
3. `runs/detect` --  This contains all runs pertaining to the training of the YoloV8 model as seen in `YoloV8.ipynb`. The `train` folders within this contains results, graphs, saved models and input arguments.
4. `dataset_methodology.txt` - This file contains further details on the data used to created the dataset seen in `Horse-Racing-2`. This includes YouTube links to the original horse race videos, links to the accompanying racecards, and details of how these YouTube videos were turned into an annotated dataset.
5. `ResNet-34.ipynb` and `ResNet-34.html` -- This is a notebook that contains a step by step breakdown of the construction of a ResNet-34 computer vision model. The file `ResNet-34.html` is a html document containing all the outputs from the notebook, which allows for the notebook outputs to be seen without the required environment and packages.
6. `YoloV8_custom.ipynb` -- This a notebook that contains the training of a YoloV8 object detection model on my custom horse racing dataset seen in `Horse-Racing-2`. No html document has been created since all desired outputs can be found in the `runs/detect` folder.
7. `linear_model_example.ipynb` and `linear_model_example.html` -- This notebook is a simple demonstration of machine learning principles and PyTorch workflow, establishing the fundamentals to allow for an understanding of computer vision models. The file `linear_model_example.html` is a html document containing all the outputs from the notebook, which allows for the notebook outputs to be seen without the required environment and packages.
8. `yolov8m.pt` and `yolov8n.pt` -- These files contain YoloV8 models. These files are not made by me but downloaded when implementing `YoloV8_custom.ipynb`.

Accompanying paper can be found [here](https://uweacuk-my.sharepoint.com/:w:/g/personal/joe2_holloway_live_uwe_ac_uk/EWWp60D_1-RCjZMNqIhb0IsBpupt5eMXYsGbOx9Np2C6wg?e=LcFXAa)

All documentation and resources used for this code has been linked in each file.

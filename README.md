## Perform the following steps in the given order:
### Option 1 (Run on Kaggle; simpler):
- Create a kaggle account and click on the link to open the notebook containing the code used for the project. This comes with the dependencies installed as well as the data is loaded already in the backend. Using this method will ensure no file handling errors. [Kaggle notebook](https://www.kaggle.com/anoubhav2198/mia-project-code)
- On clicking the link, the code file and the outputs for all 8 eight models (depending on the commit version) will be visible.
  - Version 1 - EfficientNet-B3
  - Version 3 - EfficientNet-B0
  - Version 4 - ResNet50
  - Version 5 - VGG16
  - Version 6 - InceptionV3
  - Version 9 - MobileNetV2
  - Version 11- Xception
  - Version 13- EfficientNet-B2
  


### Option 2 (Run locally):
1. Download the data (180 GB) from [dataset](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/data).
2. Open **MIA project code.ipynb** jupyter notebook (well-commented). Ensure the working directory of the data is correct in the notebook to prevent file handling errors.
3. In the **create_model()** function of code.ipynb uncomment the line for the model which you wish to run.
4. This method requires at least 13GB RAM and a high-end GPU. 

    **Note:** More errors are possible if reproduced locally (i.e., Option 2), as we had used Kaggle environment for the project and not done it locally.

    As the entire training process takes much time (for all 8 models it took around 50 hours), we have included a screenshot for each model in the **training runs** folder. This provides proof that the models were indeed run, and no manipulation of numbers was performed.

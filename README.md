**Instructions for running code**

To run the code successfully, 
1) Download Anaconda. We recommend downloading Anaconda’s latest Python 3 version (currently Python 3.5).
Install the version of Anaconda which you downloaded, following the instructions on the download page.
You have installed Jupyter Notebook. To run the notebook: start the notebook server from the command line and type in “ jupyter notebook”. You should see the notebook open in your browser.
Then load the Age and Gender Prediction notebook.
From the notebook.
2) Run the following section starting with 
a.	Data preparation and exploration.
In this section, packages like pandas, os, re, numpy, matplotlib, and seaborn should be installed using installation code “pip install (package_name)” e.g. pip install pandas, in an empty cell in the jupyter notebook. Then import data set into jupyter notebook by copying the file path where the dataset is and replacing it with the one in the first cell.
b.	Align Faces using MTCNN.
Packages like MTCNN, CV2, tensorflow, PIL has to be installed to successfully run the section. Then all cells have to be run accordingly. For, Cell 1 copy the file path where the train and dataset are and replace it with the one in the jupyter notebook. In Cell 3, load a test image from the test directory as seen in the jupyter notebook to enable cell 4 draw the bounding box for facial identification.
c.	Processing cropping and for all test and train faces 
Install and import TQDM and SHUTIL to perform cropping of the test and train faces.
d.	Transfer Learning
Run cell 1 and specify a directory to save model. In cell 2, specify the path where your development, train and validation set are located.
e.	Data 
Run cell 1 to display age gender and race for the first 5 samples in the trainset. Run cell 2 to display gender, age and race distribution.
f.	Train the Model
Import libraries as showing in the jupyter notebook accordingly. In Cell 1, each classess are defined for easy classification of our labels. The model and trained using VGG16 architecture and the number of epoch or iteration can be varied.
g.	Model Evaluation
In this section, MAE was used as the metrics of age and AUC was used as the matric of sex to succefflly evaluate the performance of our model. Run cell according to determine the MAE and AUC of your model.
h.	Prediction
In this section, load the test image directory you want to mage prediction on into the directory section in the cell. Prediction is made. And this can also be made for multiple images by also copying the image path into the directory space.


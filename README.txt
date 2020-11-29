An Application of GANs For Scenic Image Translations

Dataset: Night-time and day-time outside scenery images scrapped from google images.

Task: Develop an algorithm that is able to translate an image of a day-time scene into an image of a night-time scene and vice versa.

Method: This project will utilise a Cycle Generative Adversarial Network in order to produce the image to image translations.

Youtube Link Explaining Scenic Translations with CycleGans: https://www.youtube.com/watch?v=yLLjf-kmuAE&ab_channel=Shrek420

This project was worked on in an Anaconda environment, so in order to make sure all
packages are installed, follow the following steps:

########################################################################
0) Anaconda and git will need to be installed on the system

1) Open Anaconda Prompt

2) Navigate to the Final Project folder and run the following commands:

conda create --name adam_alex_martin python=3.7 -y

activate adam_alex_martin

pip install -r requirements.txt
########################################################################

You can now call "jupyter notebook" from the command line as usual
and open the following notebook files:
1)    "Day Night Image Translation.ipynb"
2)    "Manual Image Filtering Code/Filter Images.ipynb"

"Day Night Image Translation.ipynb" contains the main code for the project.

"Filter Images.ipynb" contains the code to manually filter images.

The folder "Data" contains a sample of the filtered dataset used in the project.

Sample images have been added to the "Manual Image Filtering Code" folder
in order to demonstrate its functionality.

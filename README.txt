** Folder Structure **
assignment3/
├── Q3        # a directory that contains raw images
|   ├── flash.JPG  # self selected image (with flash)
|   ├── noflash.JPG # self selected image (without flash)
├── Q4 # a directory that output images are saved
|    ├── csc420Q41.jpeg
|    ├── csc420Q42.jpeg
├── txtfiles         # a directory that contains all txt files for the normalized HoGs
├── a3_functions.ipynb  # jupyter notebook that visualizes the images and contains code
├── requirements.txt # a txt file that contains all the packages needed
├── README.txt       # this txt file

a3_functions.ipynb -- contains all the code for each implementation task (q3 to q4)

** How to run my code **

Suggested steps for running my functions:

1) Make sure you cd into the assignment1 directory

2) Create a virtual environment using the command below. Note that python
version that I am using is python3.7
```
conda create -n name python=3.7
```

3) Before running the code, activate your environment and make sure that the
environment contains all the necessary packages used for computations and
visualization.
Install all libraries/packages with the provided `requirements.txt`
```
pip install -r requirements.txt
```

4) IMPORTANT : Before running the Jupiter notebook `a3_functions.ipynb` if you are interested in seeing the visualization results for 1.jpg, 2.jpg, and 3.jpg (given), please make sure to download them and place it under the Q3 directory. Those 3 images were not submitted in this zip file due to the size limit of Markus. Moreover, please also make sure the following images are saved in the specified name inside the Q4 directory. 
 - https://commons.wikimedia.org/wiki/File:Sandford_Fleming_Building_2011_Toronto.jpg --> After downloading this image, rename it as "csc420Q41.jpeg"
 - https://commons.wikimedia.org/wiki/File:Uoft_SF-01.jpg --> After downloading this image, rename this as "csc420Q42.jpeg"



5) To see the results of the code,o ne can open up `a3_functions.ipynb` using the
```jupyter notebook``` command in the terminal and run the codes. There are
comments in the notebook that explains what each important line of code is doing.
> NOTE: If an Import Error (ImportError: The Jupyter Server requires tornado >=6.1.0)
is found when ```jupyter notebook``` is typed in terminal, run
```pip install tornado --upgrade``` and ```jupyter notebook``` again.


** Report.pdf **
All the visualization results in the report.pdf can be found in the images
directory

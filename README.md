## Research Question

#### Do different mallet types create different sound qualities when used to play a marimba?  Can these differences be used to train a computer to detect the type of mallet used?


The sound samples used in this notebook were obtained from the University of Iowa Electronic Music Studio website at http://theremin.music.uiowa.edu/MIS-Pitches-2012/MISMarimba2012.html.  These samples were downloaded and used in analysis using the Librosa python library.  This data was used to create a pandas dataframe for further analysis.  Visualizations were created using Librosa and matplotlib libraries.  The sklearn module is also used to use a K Nearest Neighbors Algorithm to train the computer.  As you will see with the visualizations, and with the KNN algorithm it is possible to visualize the difference between the different types of mallets used, and it is possible to train a computer to detect the type of mallet that was used to play the marimba.


### The following libraries are required to run this program
scikit-learn==0.23.2
pandas==1.1.3
numpy==1.19.2
matplotlib==3.3.2
librosa==0.8.0

Please ensure you have installed these libraries prior to running this program.

Once you have installed the libraries run all cells in Sound.ipynb.  

#### Creating the dataframe for all the notes on the marimba using three different mallet types can take a little time.  Please be patient.  Also I have found that running the KNN algorithm can take a little time.
## Research Question

#### Do different mallet types create different sound qualities when used to play a marimba?  Can these differences be used to train a computer to detect the type of mallet used?

Any professional percussionist will have a gig bag full of various types of mallets.  Mallets can vary not only by the type of handle used but also by the material on the head of the mallet as well.  A percussionist will actually select a specific mallet head based on the piece that is being played.  Each piece played requires a specific sound from the instrument and therefore a specific mallet type will be used.     

This video is a recording of Keiko Abe, the greatest marimba player.  In this video you can see she uses different techniques when playing the instrument from using split wood to yarn mallets and even using the handles of the mallets.  By listening to these different techniques you can easily hear the different sound quality pulled from the instrument.  
https://youtu.be/yOjKBRe1SuM?list=RDyOjKBRe1SuM

Mallets are to percussionists as a computer is to a programmer.   

There a lot of different steps to the analysis of sound.  By using sound analysis techniques, coupled with visualizations can we really see the difference betweeen different types of mallets being played on a marimba.  If we can see these differences can we then use a computer learning algorithm and ask the computer what type of mallet was used?


The sound samples used in this notebook were obtained from the University of Iowa Electronic Music Studio website at http://theremin.music.uiowa.edu/MIS-Pitches-2012/MISMarimba2012.html.  These samples were downloaded and used in analysis using the Librosa python library.  This data was used to create a pandas dataframe for further analysis.  visualizations were created using Librosa and matplotlib libraries.  The sklearn module is also used to use a K Nearest Neighbors Algorithm to train the computer.  As you will see with the visualizations, and with the KNN algorithm is possible to visualize difference between the different types of mallets used, and it is possible to train a computer to detect the type of mallet that was used to play the marimba.


###Creating the dataframe for all the notes on the marimbia using three different mallet types can take a little time.  Please be patient.  Also I have found that running the KNN algorithm can take a little time as well.

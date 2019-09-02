# MaStatThesisWork
 The directory contains several python notebooks used for experiments for my master thesis work.
 
     Created on 14 August 2019
     Author: Sunil Raut Kshetri
 
## Please read following information on how the notebooks files are organized.


    1. The directory contains 6 subfolders 

    2. Five of them contains notebooks files where various user-defined and wrapper functions are defined

       `ImportPythonModules`: This folder contains a python notebook file that imports all the necessary python module such sklearn, scipy, matplotlib, pandas, etc. In addtion, global variables are also defined in the notebook such as a seed number, figure sizes, ranges of parameters for DBSCAN and Spectral clustering, etc. 
   
       `PythonNotebook_InitializationOfFunctions`: This folder contains a python notebook file that runs other python notebooks to initialize both user-defined and wrapper functions that are inside other four folders, except the notebook files in the folder `PythonNotebooks_Experiments-and-Analysis`
   
       `PythonNotebooks_Experiments-and-Analysis`: This folder contains 3 subfolders each of them has notebook files that demonstates different experiments and analyses. These are the notebook files that can be run directely without any errors if the hierarchy of the folders are maintained. Please read until bullet point 4 to know the folder hierarchy.  


     3. Notebooks are run by using %run magic command where files are referenced using relative paths. It may be possible to change relative paths commands for other operating systems as these files are created in Windows 10.

     4. Please note that to run the notebook files inside one of the subfolders in the folder `PythonNotebooks_Experiments-and-Analysis`, the folder hierarchy should be maintained. For instance, in this repository, all the 6 folders are inside the top director such as `MaStatThesisWork`.  

## Usage and Caution:

    1. The first notebook file to be run is 'InitializationOfFunctions.ipynb' which is in the folder 'PythonNotebook_InitializationOfFunction'. But this file has to be run by another notebook in the location of two level inside in the directory hierarchy for successful operations otherwise errors may occur. After running this file, all the user defined functions will be available for the use in subsequent setps or analysis. 

    2. Always run this file `InitializationOfFunctions.ipynb`  before doing anything, i.,e., if you change a function or create a new function always save the updated notebook files and then run 'InitializationOfFunctions.ipynb' file in order to see the effect of changes made recently.

## To Directely Access The Results

 1) Go to the folder PythonNotebooks_Experiments-and-Analysis that contains 3-subfolders that hold all the resuts. 
 
 2) For example, the subfolder AnalysisOf2DimensionalDatasets constains IPython Notebook files for three separate analyses. 
 
 3) Similarly, other subfolders hold the results of High dimensional dataseta and the case study.

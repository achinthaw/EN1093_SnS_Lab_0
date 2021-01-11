# Signals and Systems
This repository contains the resources requried for the orientation session for the Signals and Systems labs for the ENTC19 batch. Please follow the following instructions to access these resources.

## Prerequisits
* A google account (a google drive with a substantial space available).
* A working internet connection.

## Instructions
* Make a folder called "EN1060_Signals_and_Systems_Labs_190XXX" in your google drive. (Skip this if you have this folder in your drive already)
* Inside "EN1060_Signals_and_Systems_Labs_190XXX" folder, make a folder called "Orientation". (i.e.EN1060_Signals_and_Systems_Labs_190XXX/Orientation)
* Inside the "Orientation" folder, open a new colab file.
* Name this as "Clone_File.ipynb".
* Connect to a run time in the newly created notebook.
* Mount the google drive by running the following code.

```
from google.colab import drive
drive.mount('/content/drive')
```
* Navigate to the "Orientation" folder using the following command. Note : replace "/path/to/EN1060_Signals_and_Systems_Labs_190XXX/Orientation" with the true path.
```
% cd /path/to/EN1060_Signals_and_Systems_Labs_190XXX/Orientation
```
* Clone this github repository to the current folder.
```
! git clone https://github.com/achinthaw/SignalsAndSystems.git
```
* Close the "Clone_File.ipynb" and open the colab file ("Introduction_to_Numpy_&_Matplotlib.ipynb") inside the newly cloned repository.
Looking forwards to seeing you at class! :)

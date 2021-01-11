# Signals and Systems
This repository contains the resources requried for the orientation session for the EN1093 Signals and Systems lab classes. Please follow the following instructions to access these resources.

## Tips
Be familiar with Google Colab and using GitHub before starting this lab. 

## Prerequisits
* A google account (a google drive with a substantial space available).
* A working internet connection.

## Instructions
* Make a folder called "EN1060_Signals_and_Systems_Labs_190XXX" in your google drive. (Skip this if you have this folder in your drive already)
* Inside "EN1060_Signals_and_Systems_Labs_190XXX" folder, make a folder called "Orientation". (i.e.EN1060_Signals_and_Systems_Labs_190XXX/Orientation)
* Open the "Clone_File.ipynb" that we created during the Introduction to Colab session.
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
! git clone https://github.com/achinthaw/EN1093_SnS_Lab_0.git
```
* Close the "Clone_File.ipynb" and open the colab file ("Introduction_to_Numpy_&_Matplotlib.ipynb") inside the newly cloned repository.

Looking forwards to seeing you at class! :)

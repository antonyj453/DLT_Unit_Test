# DLT_Unit_Test
## Table of contents
* [Cloning Repo](#Cloning-Repo)
* [Testing python script](#Testing-python-script)

## Cloning Repo
*  Before start testing we need python script for testing. This can can be clonned from the [github profile](https://github.com/dlt-hub/dlt/tree/master/tests/load/pipeline)
*  To clone gitub use the command ```gitclone https://github.com/dlt-hub/dlt.git```
*  Go to your terminal create a folder in the directory. To create a folder use the command ```mkdir <folder_name>```
*  After creating use the ```gitclone``` command
*  Navigate to the clonned folder
*  Use ```ls``` command to list all contents in the directory
*  use ```cd``` to navigate to each folder and use ``` cd ..``` to move backward
  
## Testing python script
* Navigate to the folder ```tests/load/pipeline```
* We can see the python script named ```test_merge_disposition.py```
* We are going to use ```pytest``` in our programme
* To use pytest, we have to install the pytest module
* To install pytest module, use command ```pip install pytest```
* We use pytest for auto-discovery of test modules and functions.  For more details [pytest](https://docs.pytest.org/en/7.4.x/)
* To run the script use the command ```pytest -m test_merge_disposition```
* If no issues are there, we can the expected result on the terminal
* Most common issue will be ```ModuleNotFoundError: No module named 'tests'```
* We have to use ```pytest``` instead of ```python or python3``` so that we can get rid of that error mentioned in the above step
* Finally make sure all the imports from other files and folder structure in proper way.


# **RadVis-3D**

## Contributors: 
   - [x]  **Abdelrahman Elewah**
   - [x]  **Abeer Badawi**
   - [x]  **Haytham Aboulabbas**
  

## **We propose a RadViz3D visualization method, we distributed uniformly the N points on the surface of the sphere, then we obtained formulas for x, y, and z mappings using scatter 3D method.**


## *Follow the below simple steps to run the code:*

### 1- open the following link [link to the code in jupyter notebook](https://mybinder.org/v2/gh/abeerbadawi/RadVis3D/a8d78446221b44e679decfb794d15e035d2aa040)

### 2- open the Function_RadVis3D.ipynb to check the core code explained in detail. In addition to all libraries you need to import. Run this code first to ensure that all libraries and code are working.

### 3- Once the Function_RadVis3D ran successfully, you can now run any of the folders (the folders are named with the dataset name) with a total of 20 datasets

### 4- Example:
    * Open Abalone Dataset folder
    * Check the dataset by clicking on the file called abalone.csv 
    * Open Abalone Data Set.ipynb to run the code
    * The code consist of two parts
        1- The first part simply calls the core function
        2- The second part calls the dataset then divide the dataset to y (labels) and X (the variables)
        3- We assume the boundary points with 10000 point
        4- We call our function (RadViz3D) with the given inputs to plot the 3D and 2D visualization successfully
        
### 5- Hint: To plot a 3D visualization the dataset should consist of one label only. Some of the datasets had more than one label so we used Label Encoder technique to Encode other labels with a range of values to plot them accurately ###

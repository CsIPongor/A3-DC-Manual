# <ins>A3-DC</ins>
A3-DC is a software to analyze object based colocalization in multichannel microscopy images. The goal of the software is to process large datasets, so processing can be run on individual images and or in batch.

Cite:<br>
 > ["Dijkstra, E. W. (1968). Go to statement considered harmful. Communications of the ACM, 11(3), 147-148."](https://dl.acm.org/doi/10.1016/S0164-1212%2801%2900136-4)

## <ins>Installation</ins>
First download the A3-DC install from the following link:<br>
[Download installer.](https://google.com)<br>

Run installer and follow the instructions below. Depending on the computer setup the installer might have to be run as **administrator**. When using Antivirus software an exception might have to be added for the installer.<br>

![using a color picker](./Images/1_Install_short.gif)

## <ins>Working with workflows</ins>

Main functions of the software are grouped into workflows. Users can create new workflows, save them so settings can be used to analye multiple datasets by loading them. In this section we will show how worklows work and the main components of the graphical user interface (GUI) through an image segmentation workflow that can be used to test different segmentation methods. 

### <ins>Starting a New Workflow</ins>

 After starting A3-DC a new workflow can be started using the "New Workflow" menupoint in the "File" menu (**File->New Workflow**) or by  using the new file button on the quick access bar (firt element). For now we will run a workflowcolocalization analysis using tiff files so please select the workflow called "Test_Thresholds_Tiff" (see below). The left section of the GUI is dedicated to set workflow settings. Each step in the workflow has a dedicated drop-down box that can be opened and closed (see below).
 
![using a color picker](./Images/1.1_Workflows_open.gif)<br>

### <ins>Saving and Loading Workflows</ins>
Workflows can be saved to run them on multiple iamge sets or for documentation porpouses. These workflows can be later loaded and after modifying the paths they can be rerun on other images.<br>
![using a color picker](./Images/1.10_Workflows_Workflow operations.gif)<br>

###<ins>Themes</ins>
The user interface has a bright and a dark theme that users can change by pressing on the dark/bright circle on the quick access bar.<br>
![using a color picker](./Images/1.11_Workflows_Themes.gif)<br>


### <ins>Workflow Settings</ins>
To follow this tutorial please download test image:<br>
[Download test image.](https://google.com)<br>

If not already open please load the "Test_Thresholds_Tiff" workflow in A3-DC. Each step in the workflow has a drop-down box that can be opend by clicking the black triangle to the left side of each box. As a first step we will set the file path and the path to where results will be saved using the first two workflow elements, please see below:<br>
![using a color picker](./Images/1.2_Workflows_settings.gif)<br>


### <ins>Segmentation Settings</ins>
Next we have to select the image channels that will be used to test different segmentation methods using the "Source" workflow component. In this case channel 1 and 2:<br>
![using a color picker](./Images/1.3_Workflows_Source.gif)<br>

The following two workflow components are used to select thresholding method, one for each channel. Thresholding methods can be chosen from a drop-down menu. If one wants to set a manual threshold, the value given in the input field (this value will only be used if the "Manual" thresholding menu is used. The thresholding method can be rum slice by slice or using the entire image stack set using a switch. The thresholding values and images can be saved to the output directory for further analysis using the aproppriate swithches. In our case we will choose the "Otsu" method for each channel: <br>
![using a color picker](./Images/1.4_Workflows_Thresholding.gif)<br>


### <ins>Running workflows</ins>
Workflows can be run in single image or batch mode using the play or fast-forward buttons. Now lets run the workflow in single image mode:<br>

![using a color picker](./Images/1.5_Workflows_Running.gif)<br>

In batch mode all images will be processed within the directory of the image that has been first opened. <br>

The log window can be used to check for the property of the images and the threshold values resulting from the segmentation procedure.<br>
![using a color picker](./Images/1.6_Workflows_Results.gif)<br>

### <ins>3D Visualization</ins>
Results of the segmentation gan be shown using the final workflow element, where the raw image data and thresholding can be visualized in 3D. In case the workflow is too long while hovering the mouse over the workflow one can scroll up and down using the scroll wheel of the mouse.
Each image stack has a toggle switch to show or hide it from view. Underneath the switch there is a slider to set Brightness and contrast. For **Manual** thresholding the intensity level can be determined using the lower intensity level of the slider.<br>
![using a color picker](./Images/1.8_Workflows_3D_view.gif)<br>

3D stacks can be rotated, zoomed and dragged. Images can be **rotate**d by clicking on the image with the mouse button and moving the mouse. and one can **zoom** using the scroll button. To drag image click on the image with the right mose button and move the mouse.<br>
![using a color picker](./Images/1.8_Workflows_3D_view_II.gif)<br>

## <ins>Colocalization Analysis</ins>

For now we will run a colocalization analysis using tiff files so please select the workflow called "Colocaize_Tiff" (see below). The left section of the GUI is dedicated to set workflow settings. Each step in the workflow has a dedicated drop-down box that can be opened and closed (see below).
![using a color picker](./Images/2.1_Colocalization_open.gif)<br>

### <ins>General Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Segmentation Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Object Analysis Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Colocalization Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Results</ins>

## <ins>Testing Segmentation methods</ins>
# <ins>A3-DC</ins>
A3-DC is a software to analyze object based colocalization in multichannel microscopy images. The goal of the software is to process large datasets, so processing can be run on individual images and or in batch.

Cite:<br>
 > ["Dijkstra, E. W. (1968). Go to statement considered harmful. Communications of the ACM, 11(3), 147-148."](https://dl.acm.org/doi/10.1016/S0164-1212%2801%2900136-4)

## <ins>Installation</ins>
First download the A3-DC install from the following link:<br>
[Download installer.](https://google.com)<br>

Run installer and follow the instructions below. Depending on the computer setup the installer might have to be run as **administrator**. When using Antivirus software an exception might have to be added for the installer.<br>

![using a color picker](./Images/1_Install_short.gif)

## <ins>Working with workflows</ins>

Main functions of the software are grouped into workflows. Users can create new workflows, save them so settings can be used to analye multiple datasets by loading them. In this section we will show how worklows work and the main components of the graphical user interface (GUI) through an image segmentation workflow that can be used to test different segmentation methods. 

### <ins>Starting a New Workflow</ins>

 After starting A3-DC a new workflow can be started using the "New Workflow" menupoint in the "File" menu (**File->New Workflow**) or by  using the new file button on the quick access bar (firt element). For now we will run a workflowcolocalization analysis using tiff files so please select the workflow called "Test_Thresholds_Tiff" (see below). The left section of the GUI is dedicated to set workflow settings. Each step in the workflow has a dedicated drop-down box that can be opened and closed (see below).
 
![using a color picker](./Images/1.1_Workflows_open.gif)<br>

### <ins>Saving and Loading Workflows</ins>
Workflows can be saved to run them on multiple iamge sets or for documentation porpouses. These workflows can be later loaded and after modifying the paths they can be rerun on other images.<br>
![using a color picker](./Images/1.10_Workflows_Workflow operations.gif)<br>

###<ins>Themes</ins>
The user interface has a bright and a dark theme that users can change by pressing on the dark/bright circle on the quick access bar.<br>
![using a color picker](./Images/1.11_Workflows_Themes.gif)<br>


### <ins>Workflow Settings</ins>
To follow this tutorial please download test image:<br>
[Download test image.](https://google.com)<br>

If not already open please load the "Test_Thresholds_Tiff" workflow in A3-DC. Each step in the workflow has a drop-down box that can be opend by clicking the black triangle to the left side of each box. As a first step we will set the file path and the path to where results will be saved using the first two workflow elements, please see below:<br>
![using a color picker](./Images/1.2_Workflows_settings.gif)<br>


### <ins>Segmentation Settings</ins>
Next we have to select the image channels that will be used to test different segmentation methods using the "Source" workflow component. In this case channel 1 and 2:<br>
![using a color picker](./Images/1.3_Workflows_Source.gif)<br>

The following two workflow components are used to select thresholding method, one for each channel. Thresholding methods can be chosen from a drop-down menu. If one wants to set a manual threshold, the value given in the input field (this value will only be used if the "Manual" thresholding menu is used. The thresholding method can be rum slice by slice or using the entire image stack set using a switch. The thresholding values and images can be saved to the output directory for further analysis using the aproppriate swithches. In our case we will choose the "Otsu" method for each channel: <br>
![using a color picker](./Images/1.4_Workflows_Thresholding.gif)<br>


### <ins>Running workflows</ins>
Workflows can be run in single image or batch mode using the play or fast-forward buttons. Now lets run the workflow in single image mode:<br>

![using a color picker](./Images/1.5_Workflows_Running.gif)<br>

In batch mode all images will be processed within the directory of the image that has been first opened. <br>

The log window can be used to check for the property of the images and the threshold values resulting from the segmentation procedure.<br>
![using a color picker](./Images/1.6_Workflows_Results.gif)<br>

### <ins>3D Visualization</ins>
Results of the segmentation gan be shown using the final workflow element, where the raw image data and thresholding can be visualized in 3D. In case the workflow is too long while hovering the mouse over the workflow one can scroll up and down using the scroll wheel of the mouse.
Each image stack has a toggle switch to show or hide it from view. Underneath the switch there is a slider to set Brightness and contrast. For **Manual** thresholding the intensity level can be determined using the lower intensity level of the slider.<br>
![using a color picker](./Images/1.8_Workflows_3D_view.gif)<br>

3D stacks can be rotated, zoomed and dragged. Images can be **rotate**d by clicking on the image with the mouse button and moving the mouse. and one can **zoom** using the scroll button. To drag image click on the image with the right mose button and move the mouse.<br>
![using a color picker](./Images/1.8_Workflows_3D_view_II.gif)<br>

## <ins>Colocalization analysis</ins>

For now we will run a colocalization analysis using tiff files so please select the workflow called "Colocaize_Tiff" (see below). The left section of the GUI is dedicated to set workflow settings. Each step in the workflow has a dedicated drop-down box that can be opened and closed (see below).
![using a color picker](./Images/2.1_Colocalization_open.gif)<br>

### <ins>General Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Segmentation Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Object Analysis Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Colocalization Settings</ins>
![using a color picker](./Images/giphy.gif)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### <ins>Results</ins>

## <ins>Testing Segmentation methods</ins>

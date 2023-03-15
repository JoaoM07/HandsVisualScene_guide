## Step-by-step guide to reproduce our data analysis process ##

We recommend running the analysis in Google Colab. Colab is Google's online platform for writing and running code. It allows you to use high-end hardware while linking with Google Drive where you can store your data. Both of these will require a Gmail account. The scripts can also be run on your machine using Jupyter Notebooks. You will need to change the filepaths to where you have saved them on your machine.

### Step 1. Download the Epic Kitchens hand-object annotations files ###
(The duration of this step depends on your internet connection as this requires the download of a very large ZIP file - 10Gb)

  1.1 - Use the url below to access the Epic Kitchens page hosting the file:
  https://data.bris.ac.uk/data/dataset/3l8eci2oqgst92n14w2yqi5ytu
  
  1.2 - Click on the 'Complete download' button (in green). 

  1.3 - Unzip the file and extract its content to a folder in your hard drive. This is the original dataset from which we extracted the data for our analysis.

### Step 2. Upload the dataset onto your Google Drive ###

  2.1 - Access your Gmail account. On the right top corner, you should see an icon with nine dots. Click on it and select Drive.

  2.2 - You should now be inside your Google Drive. You will need to create some folders. On the top left corner click on the 'plus' sign and select 'New Folder' on the dropbox. Name the folder 'hand-objects'. Enter the 'hand-objects' folder by clicking on the icon and create another folder called 'detections_root' by repeating the same process. Enter the 'detections_root' folder and upload all the folders from the zip file you downloaded and extracted to your hardrive in step '1.1'. Drag and drop the folders onto your Google Drive space.
  
### Step 3. Running our analysis ###

  3.1 - Download the Jupyter Notebooks containing our analysis:
     VisualField_Methods0.ipynb \
     VisualField_Methods_Proportions.ipynb \
     VisualField_Methods_Stats_Analysis.ipynb \
     PlottingAndFigures.ipynb 
     
  3.2 - Create a folder in your Google Drive called 'LVS_notebooks'. Upload the above four files onto the 'LVS_notebooks' folder. 
  
  3.3 - Run the code in the Notebooks in the same sequence as the list above. Inside each Notebook you will find some information regarding the analysis. Code will be contained in separate cells (cell = each box containing code). To run the code in each cell, press the 'Shift' and the 'Enter' keys at the same time. Wait for the previous cell to finish running its code before you run the next cell. 

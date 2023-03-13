## Step-by-step guide to reproduce our data analysis process ##

**'O hand, where art thou? – Mapping hand location across the visual scene, during common activities' (Accepted for publication)**

We recommend running the analysis in Google Colab. Colab is Google's online platform forwriting and running code in Python language. It allows for using high-end processors and links with Google drive where you can store your data. Both of these will require a Gmail account.

### Step 1. Download the Epic Kitchens hand-object annotations files ###
(The duration of this step depends on your internet connection as this requires the download of a very large ZIP file - 10Gb)

  1.1 - Use the url below to access the Epic Kitchens page hosting the file:
  https://data.bris.ac.uk/data/dataset/3l8eci2oqgst92n14w2yqi5ytu
  
  1.2 - Click on the 'Complete download' button 

  1.3 - Unzip the file and extract all the folders to a directory of your choice

### Step 2. Upload the data onto your Google Drive ###

  2.1 - Access your mail account. On the right top corner, you should see an icon with nine dots. Click on it and select Drive.

  2.2 - You should now be inside your Google Drive. You will need to create some folders inside your Google Drive. On the top left corner click on the 'plus' sign and select 'New Folder' on the dropbox. Name the folder 'hand-objects'. Enter the 'hand-objects' folder by clicking on the icon and create another folder called 'detections_root' by repeating the same process. Enter the 'detections_root' folder and upload all the folders from zip file you downloaded and extracted to your hardrive. This will involve drag and dropping the folders onto your Google Drive space.
  
### Step 3. Run the analysis ###

  3.1 - Download the following files to your computer: \
     [VisualField_Methods0.ipynb]() \
     [VisualField_Methods_Proportions.ipynb]() \
     [VisualField_Methods_Stats_Analysis.ipynb]() \
     [PlottingAndFigures.ipynb]() \
     
  3.2 - Create a folder in your Google Drive called 'LVS_notebooks'. \
  
  3.3 - Upload the above 4 files into 'LVS_notebooks' by drag and dropping the files,

# PDSProject

## Data Access and Storage

### Google Drive Folder
The datasets and model files for this project are stored in a shared Google Drive folder.  
You can access the folder using the following link:

[Access Data on Google Drive](https://drive.google.com/drive/folders/115BAdMiesn--fk8bPIvOY778xpMLTmTQ?usp=drive_link)

### Contents of the Folder
- **Raw Data**: Contains the original datasets used for analysis (located in `raw_data/`).
- **Cleaned Data**: Contains processed datasets after cleaning and feature engineering (located in `cleaned_data/`).
- **Models**: Includes trained machine learning models (stored in `models/`).

### Usage Instructions
1. **Mount Google Drive in Google Colab**:
   Use the following code snippet to access the folder in your Colab notebook:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

   # Navigate to the folder
   folder_path = '/content/drive/My Drive/group_wqd7001'

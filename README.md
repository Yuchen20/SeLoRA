# SeLoRA Repository

This repository serves as a presentation of the SeLoRA codebase.

The code encompasses the entire training procedure. Variable listed below needs to be modified for your sepecified dataset.

### Key Variables:

- **Main_Path**: The path to the folder containing the dataset.
  
- **Data_storage**: The path to the datasets under the main path.

- **save_result_path**: The path for saving the results.

- **folder_name**: The folder where the results of the current experiment will be stored.

### Dataset Configuration:

Make sure to modify the Datasets section for specific dataset configurations.

### Reports variable:

The 'reports' variable is a `pd.Dataframe` with two columns:

- **filename**: The file name of each image.

- **findings**: The prompt corresponding to the image.

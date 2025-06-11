# Protein Structure Prediction with Transformer

A deep learning pipeline for protein structure prediction based on Transformer architecture. This project includes data preprocessing, training, validation, and visualization — all built and executed in Google Colab.

---

## Project Structure

```bash
.
├── data/                        
│   ├── 01_protein_pdb_id
│   ├── 02_downloaded_filtered_protein_data   # File size limit, cannot upload
│   ├── 03_train_valid_dataset_and_staticsb   # File size limit, cannot upload
│
├── outputs/                            
│   ├── models/         # trained model weights
│   ├── plots/          # Jupyter notebooks (Colab-based)
│
├── src/ProteinPredictionTransformer         # Jupyter notebooks (Colab-based)                     
│
├── README.md
├── requirements.txt
└── .gitignore



## 🚀 Get Started

This project is designed to run in **Google Colab**. To get started, follow these steps:

1. **Install dependencies**  
   In your Colab notebook, install the required packages by running:
   
   ```python
   !pip install -r requirements.txt
   ```

2. **Prepare the data**  
   The `data` folder includes a list of protein IDs from the immunoglobulin family. Due to file size limitations, the full protein data and the processed training/validation datasets are not uploaded here.
   You can generate and download these datasets using the following notebooks in the `utils_data_preprocess` folder:
   
   - `02_download_with_id_and_filter.ipynb`: Downloads and filters protein data using the provided IDs.
   - `03_preprocess_and_split_train_valid_dataset.ipynb`: Processes the raw data and splits it into training and validation sets.

3. **Organize your files in Google Drive**  
   After preprocessing the data, place the resulting files into your Google Drive. Make sure to configure the correct file paths in your Colab notebooks.

4. **Run the model**  
   Navigate to the `src/ProteinPredictionTransformer` directory and run the notebooks to begin training and testing the Transformer-based protein structure prediction model.



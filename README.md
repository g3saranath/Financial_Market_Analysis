# Leveraging Sparse and Dense Vectors for Real-Time Financial Market Analysis

## Environment Setup:
Creating a conda environment or python venv. Implement the following on `terminal/cmd`.
If Conda: 
```
conda create -n fin_ana
conda activate fin_ana
conda install pip
pip install "qdrant-client[fastembed]>=1.8.2"
pip install -r requirements.txt
```

If Python venv:
```
python3 -m venv .fin_ana
source .venv/bin/activate
pip install "qdrant-client[fastembed]>=1.8.2"
python install -r requirements.txt
```

## Dataset:
Sample dataset has alredy been prepared for use which is located in /data directory. 
The data consists of Stock prices and News articles of Apple from 2023-2024. 

If you would like to collect a different timeline of data, or different company profile, please run the `dataset_prep.ipynb` file.

## Code: 
Please go to `financial_analysis.ipynb` file in the directory to run the end-to-end example of financial analysis with Dense and Sparse Vectors using Qdrant. 




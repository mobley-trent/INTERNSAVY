# INTERNSAVY
This repository is a collection of projects done during my internship at Internsavy.

## Projects:
1. Customer Segmentation using K-Means
2. Graduate Admission Analysis
3. Cricket World Cup 2019 Analysis

## Kaggle API 
To access the data remotely, I made use of the Kaggle API which pulls the data directly into Google Colab. You will need to have an account on Kaggle to use the API if you wish to do the same. The option to use the data locally is available if you clone the repo.
If you do, run this code in Colab to upload your Kaggle API key:

```
from google.colab import files
files.upload() # upload kaggle.json

!pip install -q kaggle
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!ls ~/.kaggle
!chmod 600 /root/.kaggle/kaggle.json

!kaggle kernels list — user YOUR_USER — sort-by dateRun
```

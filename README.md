# medgemma-cbis-ddsm
Repository containing the base code for EDA and fine-tuning of MedGemma 4B variant with CBIS-DDSM mammography dataset

- The file **cbisddsm-calc-medgemma-tuning-v2.ipynb** contains the necessary code to load calcification data, fine-tune MedGemma on it and evaluate it on test data
- The file **medgemma-masses-finetune.ipynb** contains the necessary code to load masses data, fine-tune MedGemma on it and evaluate it on test data
- The file **cbisddsm-eda.ipynb** contains the necessary code to perform an EDA on CBIS-DDSM dataset from Kaggle

The links to the fine-tuned MedGemma models on calcifications and masses are available in HuggingFace. Check the folder **models/calcifications** and **models/masses** to find the related URLs to HuggingFace

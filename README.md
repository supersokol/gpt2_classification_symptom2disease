# Supersokol's GPT-2 Fine-Tuning for Classification on Symptom2Disease Kaggle dataset implementation notebook
Welcome! 

Solution based on [this post about GPT-2 Fine-Tuning](https://gmihaila.github.io/tutorial_notebooks/gpt2_finetune_classification/)
And [Symptom2Disease dataset from Kaggle](https://www.kaggle.com/datasets/niyarrbarman/symptom2disease) was used to train and validate the model.
Symptom2Disease dataset contains 1200 text descriptions of symptoms of 24 different diseases.
With 13 (sic!) epochs of fine-tuning GPT-2 on CPU I've got validation accuracy of 83% on disease classification task (Train/Validation split is 66/33)

The primary objectives of this implementation project are as follows:

* Gain a deeper understanding of the transformer architecture and attention mechanisms.
* Fine-tune GPT-2 and analyze its performance on classification task.
* Showcase my coding skills and ability to comprehend ML concepts.

A quick breakdown of each of the files:

* `Symptom2Disease.csv` contains the [Symptom2Disease dataset from Kaggle](https://www.kaggle.com/datasets/niyarrbarman/symptom2disease)
* `gpt2-classification.ipynb` contains the actual GPT-2 model fine-tuning code with examples in separated blocks.


#### Dependencies 
```bash
pip install -r requirements.txt
```
Tested on `Python 3.7.9`.

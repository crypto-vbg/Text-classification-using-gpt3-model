# Text-classification-using-gpt3-model
1. Clone the repository to your local machine using the command
`git clone https://github.com/gmihaila/tutorial_notebooks.git`

2. Navigate to the directory containing the GPT-2 fine-tuning code using the command 
`cd tutorial_notebooks/gpt2_finetune_classification`

3. Create a new virtual environment using the command
`virtualenv -p python3 venv`

4. Activate the virtual environment using the command
`source venv/bin/activate`

5. Install the required dependencies using the command 
`pip install -r requirements.txt`

6. Download the pre-trained GPT-2 model checkpoint from the link provided in the README file and save it to the directory `gpt2_finetune_classification/checkpoint/`

7. Download the classification dataset (in CSV format) and save it to the directory 
`gpt2_finetune_classification/data/`

8. Preprocess the dataset by running the script 
`preprocess_classification_dataset.py` 
using the command 
`python preprocess_classification_dataset.py`

9. Fine-tune the GPT-2 model on the preprocessed dataset by running the script **gpt2_classification.py** using the command python `gpt2_classification.py`

10. After the fine-tuning is complete, evaluate the performance of the model on the test set by running the script **evaluate_classification.py** using the command `python evaluate_classification.py`

## References

- Mihaila, G. (2020). GPT-2 Fine-Tuning for Text Classification [Tutorial]. Retrieved March 10, 2023, from https://gmihaila.github.io/tutorial_notebooks/gpt2_finetune_classification/

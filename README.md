# language_model_finetuning
Scripts for fine-tuning pretrained language models on custom data sets, e.g. 


* for fine-tuning [Sci-Bert](https://github.com/allenai/scibert) on the [COVID-19 Open Research Dataset (CORD-19)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge) using the [Hugging Face Transformer](https://github.com/huggingface/transformers) library.
* for fine-tuning Bert on the [ACL Anthology Reference Corpus](https://acl-arc.comp.nus.edu.sg/).

Examples are provided for using the models (SciBERT, SciBERT fine-tuned, and BERT-"original") for [extractive summarization](https://github.com/Nikoschenk/language_model_finetuning/blob/master/scibert_summaries.ipynb) (BERT) and [text-generation](https://github.com/Nikoschenk/language_model_finetuning/blob/master/gpt2_fine_tuner.ipynb) (GPT-2).

## Credits:
Copyright for papers belongs to [ACL](https://acl-arc.comp.nus.edu.sg/). Adaptations of original notebooks by [Chris Callison-Burch](https://github.com/computational-linguistics-class/computational-linguistics-class.github.io) and [Derek Miller](https://github.com/dmmiller612/bert-extractive-summarizer).

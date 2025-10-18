# Hugging-Face-LLM-Transformer Fine-Tuning

A repo to store Colab notebooks and code of my Hugging Face fine-tuned transformer models for different tasks.

Tasks
------------

- text generation
- text classification
- token classification (NER)
- Question and Answering (SQuAD)

link to my hugging face: https://huggingface.co/ae-314/models 

link to the official HuggingFace LLM course: https://huggingface.co/learn/llm-course/en/chapter1/1

transformer-fine-tuning:
-------------------------

- Contains Google Colab notebooks from the official hugging face LLM course
- Copy of sequence classification notebook (fine-tuned DistilBERT on the imdb dataset to classify reviews as either positive or negative)
- imdb_review_classifier_demo notebook (We use my freshly fine-tuned DistilBERT for text classification with a pipeline and 3 custom film review examples as a demo)
- token_classification_wnut_model notebook and .py file (token classification for Named Entity Recognition fine-tuned model)
- token_classification_wnut_model_demo notebook and .py file (load the model from the Hub + 4 examples of using the model-- directly and with a pipeline)
- qa_squad_model_demo.ipynb and qu_squad_model_demo.py (SQuAD fine-tuned model for question and answering -- 1 example)

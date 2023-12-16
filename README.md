# FLAN-T5 Tutorial: Fine-Tuning

- T5 stands for "Text-to-Text Transfer Transformer,". It is a large language model developed by Google. 
- Google created Flan-T5 by training the original T5 architecture on a wide variety of tasks. This finetuning method is called instruction finetuning, and has been shown to improve model performance significantly on previously unseen tasks.


**fine-tune FLAN-T5 for a question-answering**

Multiple formats of FLAN-T5 models are available on Hugging Face: 

- google/flan-t5-small (80m parameters, 300MB)
- google/flan-t5-base (250m parameters, 990MB)
- google/flan-t5-large (780m parameters, 1GB)
- google/flan-t5-xl (3b parameters, 12GB)
- google/flan-t5-xxl (11b parameters, 80GB)
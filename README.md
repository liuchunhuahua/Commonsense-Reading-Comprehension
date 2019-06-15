# Multi-Finetune BERT

This model adapts two-staged fine-tune on pre-trained Bert model. The first stage is to fine-tune the language model on in-domain machine reading comprehension dataset (such as RACE). The second stage is to fine-tune the classifier on target-task (MCScript2.0) with some other commonsense dataset (such as SWAG) assisted. 

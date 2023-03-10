This is an updated jupyter notebook based on https://github.com/lvwerra/trl/blob/main/examples/sentiment/notebooks/gpt2-sentiment.ipynb. 
It includes a custom step method to reduce GPU memory usage when training large models with limited GPU memory. 
Also, during training, the code will upload the fine-tuned model to Huggingface at certain epochs in case kernel dies. 

Note:  The latest fine-tuned model can be used as the new starting point for training instead of starting from scratch.

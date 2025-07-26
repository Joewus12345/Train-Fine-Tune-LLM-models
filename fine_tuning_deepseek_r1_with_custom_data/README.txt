In this project, Fine tuning of LLM (deepseek-r1 model) with custom data is done with Unsloth library using LoRA (Low-Rank Adaptation)
technique. SFTTrainer (trl) etc. Unsloth offers some optimized approach for fine tuning, it reduces memory usage and makes fine-tuning 
possible even on slower GPUs. For fine tuning, mental health counseling conversations data from hugging face are used after proper formatting 
and structuring. Model was trained for 1 complete epoch on Google colab GPU. Before fine-tuning, model was tested with some mental health 
issues related queries and responses were observed and recorded. Model was evaluated with the same queries after fine tuning and we could
see the effect of fine-tuning in the LLM's responses and also the quality of responses.

Link of the original blog based on which this is done: https://www.kdnuggets.com/how-to-fine-tune-deepseek-r1-custom-dataset






Project Summary:
•	GPT-2 model is tuned using a mixture of synthetic optical module data and actual data from Cell Site Router 
•	Model is tuned for learning laser bias current, channel power of the optical module. 
•	The objective is to make a fine-tuned model from GPT-2, that is then distilled and pruned. 
•	The distilled pruned version of model is then quantized to run in 4bit mode in an embedded system with small foot print compute resources. 
•	Last step is to demonstrate an agent answering field technician’s troubleshooting queries.

Instructions on testing on your laptop:


1. Start with the Finetuning notebook
2. Make sure the model directories are getting created
3. Then use the compression notebook
4. Finally run the quantization notebook
5. You can try out the agent in this notebook
6. I ran it on an M1000 GPU on an old Dell precision 5510 (takes a while)
Disclaimer:  Has not been tested extensively just yet. 

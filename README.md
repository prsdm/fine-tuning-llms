Updated on 14th August 2024
# Large Language Models Notebooks
<p>
📝<a href="https://medium.com/@prasadmahamulkar/fine-tuning-phi-2-a-step-by-step-guide-e672e7f1d009">Article</a> • Models & Datasets on: 🤗<a href="https://huggingface.co/prsdm">Hugging Face</a>
</p>

This repository provides a collection of Jupyter notebooks that demonstrate how to fine-tune large language models with less minimal cost. 

fine-tuning or instruction tuning is the process where the pre-trained model is further trained on the smaller dataset to adapt its knowledge for a specific task or domain. This process tweaks the model’s parameters to perform specific tasks. In fine-tuning, there are two methods:

### Supervised fine tuning (SFT):
In SFT, the model is trained on a labeled dataset. The labeled dataset typically contains examples of instruction (input) and response (output) pairs relevant to the task. In this process, the model learns how to respond to specific instructions.

### Reinforcement Learning from Human Feedback (RLHF): 
In RLHF, the model interacts with users, generates responses, and receives feedback in the form of reinforcement signals. Basically, the model learns and improves its performance based on the feedback it receives.

### Detailed explanation of each notebook:

| LLMs                      | Description | Dataset | Notebooks | Tuned Model |
|---------------------------|-------------|---------|-----------|-------------|
| [Phi-2](https://huggingface.co/prsdm/phi-2-medquad) | This model has been fine-tuned on a Medical dataset to answer questions related to diseases and symptoms. (used SFT method) | [Dataset](https://huggingface.co/datasets/prsdm/MedQuad-phi2-1k) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prasadmahamulkar/Large-Language-Models/blob/main/Fine_tune_Phi_2_on_Google_Colab_.ipynb) | [phi-2-medquad](https://huggingface.co/prsdm/phi-2-medquad) |
| [llama-2](https://huggingface.co/prsdm/llama-2-finance) | This model has been fine-tuned on a dataset with human-generated prompts to answer questions related to general knowledge. (used SFT method) | [Dataset](https://huggingface.co/datasets/prsdm/finance-llama2-1k) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prasadmahamulkar/Large-Language-Models/blob/main/Fine_tune_llama_2_on_Colab.ipynb) | [llama-2-finance](https://huggingface.co/prsdm/llama-2-finance) |
 

### Diagram:

![diagram](https://github.com/user-attachments/assets/b84531b3-9935-4e2f-bd05-e0f88f95edb6)


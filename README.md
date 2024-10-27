# Llama2-Medical-Chatbot Setup Guide

Follow these steps to set up and run the Llama2-Medical-Chatbot project.


## Prerequisites
Ensure that Anaconda and Git are installed on your system.

## Steps
1. Open Anaconda Prompt
2. Create a New Virtual Environment
conda create -n myenv python=3.10

3. 








# Steps to set up and run the Llama2-Medical-Chatbot Project:

1. Open "Anaconda Prompt"

2. Create a new virtual environment
   conda create -n myenv python=3.10

3. Activate the environment
   conda activate myenv

4. clone the repo:
   git clone <the repo>

5. Install the required module
   pip3 install -r requirements.txt

6. pip3 install openai

7. Copy 'mental_health_Document.pdf' to data/ folder.

8. run "python ingest.py"

9. run "chainlit run model.py -w"

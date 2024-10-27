# Llama2-Medical-Chatbot Setup Guide
Follow these steps to set up and run the Llama2-Medical-Chatbot project.


## Prerequisites
Ensure that Anaconda and Git are installed on your system.
## Steps
1. #### Open Anaconda Prompt
2. #### Create a New Virtual Environment
   conda create -n myenv python=3.10
3. #### Activate the Environment
   conda activate myenv
4.  #### Clone the Repository
      git clone repository-url   
      cd repository-name
5.  #### Install Required Packages
      pip install -r requirements.txt    
      pip install openai
6. #### Add Project Files
   Copy mental_health_Document.pdf into the data/ folder.
8. #### Ingest Data
   python ingest.py
9. #### Run the Model
   chainlit run model.py -w

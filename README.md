# paraphrasing_project2022
ABSTRACT

Everyone around the world, be it students or working professionals, face problems related to 
Plagiarism. Plagiarism is the act of stealing or using other people’s content and presenting it as 
your own. This applies to all manner of content online or offline. When writing a document or 
summarizing after researching, it is always a good idea to present information in your own 
words. 

This project uses python as its base programming language because of its ease of simplicity,
power and ease of integration with the NPL (Natural Language Processing) model used.
The implemented model is called the Pegasus Model published in the PEGASUS: Pre-training 
with Extracted Gap-sentences for Abstractive Summarization by Jingqing Zhang, Yao Zhao, 
Mohammad Saleh and Peter J. Liu on Dec 18, 2019, which offers multiple customization 
parameters. It is available under the GitHub repository managed by google-research for opensource ML models. 
This project serves as a tool for everyone who wants to avoid plagiarism and rephrase their 
sentences as few words as possible

Notes on installation:

This project uses certain python libraries – ‘sentence_splitter’, ‘sentencepeice’, ‘streamlit’, ‘torch’, 
‘transformers’. To make use of the Pegasus model, we must import it from the transformers module. The 
transformers module will download the Pegasus model from the internet and occupy 2.12 GB in ROM 
stored in the hugginface directory located in C:/Users/<username>/.cache folder, therefore a stable internet 
connection is recommended. To install these packages, we use the python package manager pip (pip installs 
packages).
    
Use:
   
    1. pip install -r requirements.txt
   
After installing these dependencies, first compile the script in cmd using:
   
    1. python working.py
    
Once it compiles without any errors, view the output on your browser using:
    
    1. streamlit run working.py
    
Conclusion:

During our testing, the system satisfies our requirement to remove plagiarism as an obstacle. 
Although the system is substantially more time consuming than an online tool, it is concluded
that, on average, our system is 24.4% more effective than any online paraphrasing tool
available
    
    
We thank the existence of many sources/technologies to exist for the success of this project. 
The sources used are as follows:
1. Streamlit for web app creation: 
https://streamlit.io/
2. The hugging face community by google for the Pegasus Model: 
https://huggingface.co/docs/transformers/model_doc/pegasus
3. Jingqing Zhang, Yao Zhao, Mohammad Saleh and Peter J. Liu (Dec 18, 2019) 
PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive 
Summarization.
4. Data sets used to pre-train the Pegasus Model: 
https://huggingface.co/datasets/sshleifer/pseudo_bart_xsum/resolve/main/bart
_xsum_pl.tgz
5. Python Software Foundation: 
https://www.python.org

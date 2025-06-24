# Agentic RAG Model Testing and Tuning
The goal of this project is to benchmark the ability of various models to perform query rewriting in agentic RAG pipelines, in the form of measuring the quality of generated sub-queries by measuring the text format and retrieval recall of each set of sub-queries on a dataset.

Check `rag.ipynb` for the code.

## Results
_Measured on test set of 50 queries and expected chunks_
### Total Reward
_The sum of all reward functions defined formatting + retrieval_
![image](https://github.com/user-attachments/assets/2bbbb5db-200e-43fb-8db8-7f852d184a70)
![image](https://github.com/user-attachments/assets/54ba5c25-01b4-4d59-a51a-018bd887da69)

### Retrieval Reward
_The output of the reward function designed to measure recall of the documents_
![image](https://github.com/user-attachments/assets/f246b1ae-dfb8-497a-af06-94cf5ba31822)
![image](https://github.com/user-attachments/assets/38246026-75b5-480d-82bb-c682e7061ccb)

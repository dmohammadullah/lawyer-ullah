# Lawyer-Ullah-Chatbot-Project

![image alt](https://github.com/dmohammadullah/lawyer-ullah/blob/09ca290b840629267e7f0abaeb0a004ff97efedb/lawyer_ullah.JPG)

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/
```

### install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone

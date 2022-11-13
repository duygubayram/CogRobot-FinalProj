# About
The bloom_text2python_1.ipynb Notebook comes from [this repo](https://github.com/gtziafas/cognitive_robotics_LLM_notebooks). Here we try to
extend the prompts such that we can generate more accurate Python code.

The code_as_policies_interactive_demo.ipynb Notebook comes from the [Code as Policies](https://arxiv.org/pdf/2209.07753.pdf) paper. Here we try to
adapt it to generalise to household objects, and investigate with using a different inference model (Bloom instead of 
DaVinci).

# API Tokens

The API tokens are retrieved in the Notebooks using the `get_tokens.py` file (not in this repo).
This file contains the following functions:
```
def get_hugging_face_token():
    return PASTE_TOKEN_HERE
    
def get_open_ai_token():
    return PASTE_TOKEN_HERE
```

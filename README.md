# AaliyahSalia-CS589_W2_HW1
Project: Customer Support System: Use ChatGPT to build a web-based system that can answer questions about a website.

Here is a summary of the key points from the PDF:

# Customer Support Web Application using ChatGPT

## Objective
- Build a customer support web application that can answer questions about a website using ChatGPT models.

## Steps
- Set up Python environment with required packages
- Crawl data from target website and save as CSV
- Use text-embedding-ada-002 model to embed text data from CSV 
- Build web interface with Flask to allow users to pose questions
- Fetch relevant answers using embedded website data and text-davinci-003 model

## Implementation Details
- Developed and tested on VS Code 
- Used a smaller dataset during development to optimize token usage
- Customized embedText.py file path to use custom test data
- Tested data crawling before proceeding to next steps
- Flask app allows users to ask questions through web interface
- Queries are answered using website data embeddings and text-davinci-003 model

## Key Outcomes
- An interactive web application to provide customer support by answering user queries about a website
- Optimization of OpenAI API token usage by minimizing usage during development
- A modular and customizable implementation allowing easy adaptation to other websites

References:
https://hc.labnet.sfbu.edu/~henry/sfbu/course/machine_learning/chatgpt/slide/exercise_chatgpt.html
https://platform.openai.com/docs/tutorials/web-qa-embeddings

# DocsGPT

While OpenAI's ChatGPT is an extraordinary innovation, we can now also use OpenAI to query our own documents.

This demo app illustrates how you can use OpenAI's GPT and [🦜🔗LangChain](https://langchain.com) to process and chat with your local PDF files.

It comes preloaded with sample Amazon annual and shareholder reports in a ./files/ subfolder. You can start chatting with those or replace the files in the subfolder with your own PDFs

Load it onto your laptop and start asking the PDFs questions.  See the demo screenshots below.

## Screenshots

![Screenshot](https://github.com/alanwunsche/DocsGPT/blob/main/DocsGPT-Demo-CLI-2023-04-19-at-9.12.05%20PM.png)

## Installation

Open your Terminal application:

```git clone https://github.com/alanwunsche/DocsGPT.git```

```cd DocsGPT```

```pip install -r requirements.txt```

## Insert your OpenAI API Key

Obtain your own OpenAI API key at https://platform.openai.com

Insert your OpenAI API key into the main.py file.  

## Add your own PDFs

Add your own PDFs to the /files/ subfolder

## Run the application
```python main.py```

## 💬Chat with your PDFs

### Example questions you can ask your PDFs:

What's the most profitable business line and how much did it earn in each of 2021 and 2022?

Provide a detailed analysis of how Covid impacted the business in each of the last 2 years 

Describe in depth the company's climate strategy over the past decade

Describe the expected business benefits of the company's climate plans for the upcoming decade

## Contact
Twitter: [@alanwunsche](https://twitter.com/alanwunsche)

## Notes
You may encounter a warning "detectron2 is not installed. Cannot use the hi_res partitioning strategy. Falling back to partitioning with the fast strategy.
" but it will not prevent your app from working.



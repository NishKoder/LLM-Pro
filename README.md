# LLM-Zero-to-Hundred

<div align="center">
  <img src="logo/AI_RT.png" alt="CAIS" width="300" height="250">
</div>
This repository demonstrates different use cases and well-knonw techniques for LLMs.

### List of projects:
- [x] [WebGPT](#WebGPT)
- [x] [RAG-GPT](#RAG-GPT)
- [ ] [LLM Agent Tutorial](coming-soon): Will be added soon.
- [ ] [Multimodal ChatBot](#Multimodal-ChatBot): Will be added soon.
- [ ] [LLM Full Finetuning](coming-soon): Will be added soon.
- [ ] [PEFT: Parameter-Efficient Finetuning](coming-soon): Will be added soon.
- [ ] [LLM Pretraining](coming-soon): Will be added soon.

### List of tutorials
- [x] [LLM Function Calling Tutorial](#LLM-function-calling-tutorial)
- [x] [Vectorization Tutorial](#LLM-function-calling-tutorial)



## Project description:
<a id="WebGPT"></a>
<h3>WebGPT:</h3>
<p>
<a style=" white-space:nowrap; " href="https://github.com/Farzad-R/LLM-Zero-to-Hundred/tree/master/WebGPT"><b>WebGPT</b></a>: is a powerful tool enabling users to pose questions that require internet searches. Leveraging GPT models:

* It identifies and executes the most relevant given Python functions in response to user queries. 
* The second GPT model generates responses by combining user queries with content retrieved from the web search engine. 
* The user-friendly interface is built using Streamlit.
* The web search supports diverse searches such as text, news, PDFs, images, videos, maps, and instant responses. 
* Overcoming knowledge-cutoff limitations, the chatbot delivers answers based on the latest internet content.

Libraries: [OpenAI](https://platform.openai.com/docs/models/overview) (It uses GPT model's function calling capability) - [duckduckgo-search](https://pypi.org/project/duckduckgo-search/) - [streamlit](https://docs.streamlit.io/)

</p>

<a id="RAG-GPT"></a>
<h3>RAG-GPT:</h3>
<p>
<a style=" white-space:nowrap; " href="https://github.com/Farzad-R/LLM-Zero-to-Hundred/tree/master/RAG-GPT"><b>RAG-GPT</b></a>: is a chatbot that enables you to chat with your documents (PDFs and Doc). The project works with two types of data:

1. With documents that you have vectorized and processed beforehand.
2. With documents that you upload while chatting with the model.

Libraries: [OpenAI](https://platform.openai.com/docs/models/overview) - [Langchain](https://python.langchain.com/docs/get_started/quickstart) - [ChromaDB](https://www.trychroma.com/) - [Gradio](https://www.gradio.app/guides/quickstart) 
</p>


<a id="Multimodal-ChatBot"></a>
<h3>Multimodal-ChatBot:</h3>
This project aims to develop a versatile chatbot capable of processing text and voice inputs, generating multimodal responses (text, voice, images), and conducting web searches to deliver accurate information. Additionally, the chatbot will be equipped to analyze documents and respond to related queries.

## Tutorial description:
<a id="LLM-function-calling-tutorial"></a>
<h3>LLM Function Calling Tutorial:</h3>
<p>
<a style=" white-space:nowrap; " href="https://github.com/Farzad-R/LLM-Zero-to-Hundred/tree/master/tutorials/LLM-function-calling-tutorial"><b>LLM-function-calling-tutorial</b></a>:
    showcases the capacity of GPT models to produce executable functions in JSON format. It illustrates this capability through a practical example involving the utilization of Python with the GPT model.

Libraries: [OpenAI](https://platform.openai.com/docs/models/overview)
</p>
<a id="LLM-function-calling-tutorial"></a>
<h2>Visualizing Text Vectorization:</h2>
<p>
<a style=" white-space:nowrap; " href="https://github.com/Farzad-R/LLM-Zero-to-Hundred/tree/master/tutorials/vectorization_tutorial"><b>Visualizing Text Vectorization</b></a>: provides a comprehensive visualization of text vectorization and demonstrates the power of vector search. It further explores the vectorization on both OpenAi `text-embedding-ada-002` and the open source `BAAI/bge-large-zh-v1.5` model.

Libraries: [OpenAI](https://platform.openai.com/docs/models/overview) - [HuggingFace](https://huggingface.co/BAAI/bge-large-zh-v1.5)
</p>

## Running each project
To run the projects, you will need to install the required libraries. Follow the steps below to get started:

1. Clone the repository and navigate to the project directory.
```
git clone https://github.com/Farzad-R/LLM-Zero-to-Hundred.git
cd <yourproject>
```
2. Create a new virtual environment using a tool like virtualenv or conda, and activate the environment:
```
conda create --name projectenv python=3.11
conda activate projectenv
```
3. Install the required libraries using the following commands:
```
pip install -r requirements.txt
```
4. Then
```
cd <to each directory>
```
Follow the instructions provided for that specific project.


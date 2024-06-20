0. Intro
1. Chat
2. Chat with memory
3. Speak with document
4. ImageReading
5. ImageGen
6. Website/Wiki reading

# myGPT

  

- Process Documents

  

- Pre-processing

- HTML

- partioning, cleaning and chunking

- unstructured.io -> .md

- https://docs.unstructured.io/open-source/core-functionality/overview

- PDF

- partioning and cleaning

- llama-cloud or OpenAI -> .md

- https://cloud.llamaindex.ai/parse

- chunking

- unstructured.io

- PPTX

- partioning and cleaning

- llama-cloud or OpenAI -> .md

- chunking

- unstructured.io

- txt

- partioning, cleaning and chunking

- unstructured.io -> .md

- image

- partioning and cleaning

- llama-cloud or OpenAI -> .md

- chunking

- unstructured.io

- .md

- partioning, cleaning and chunking

- unstructured.io -> .md

- Processing

- Llama-index

- https://docs.llamaindex.ai/en/stable/api_reference/readers/file/?h=unstructured.io#llama_index.readers.file.UnstructuredReader

- Embed

- see this video -> https://www.youtube.com/watch?v=LzRpTNV74Ck

- choose embedding -> https://huggingface.co/spaces/mteb/leaderboard

- Vector Store

- Pinecone

- https://docs.pinecone.io/integrations/llamaindex#load-the-data

  

- SimpleChat

  

- **llama-index only**

- or directly with Fireworks or groq

  

- SimpleChat with Documents

  

- Process documents like above

- Try ReAct or Condense Plus Context Mode

- ReAct -> https://docs.llamaindex.ai/en/stable/examples/agent/react_agent/?h=react

- Makes sense if something more than only RAG

- Another example with langchain-> https://github.com/paryska99/RAG_for_QA_local/tree/master

- Understand whether pipeline / chain are needed

- Llama pipeline -> https://github.com/paryska99/RAG_for_QA_local/tree/master

  

- Adding JSON mode

  

- SQL mode

  

- Github mode

  

Who you are: you are a financial advisor for a family

Your job: read documents and breakdown expenses into categories

Categories:
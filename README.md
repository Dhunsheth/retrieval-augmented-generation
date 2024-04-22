# Retrieval Augmented Generation Model     
     
Created a retrieval augmented generation model using Hugging Face Gemma-7b LLM   
    
This project presents the development and evaluation of a Retrieval Augmented Generation (RAG) model, designed to enhance information retrieval and response accuracy for hockey-related queries. Traditional Large Language Models (LLMs) often struggle when queried about real-time information, creating a need for a more precise solution. Our RAG model integrates an external up-to-date, hockey-specific knowledge base with a generative LLM to improve data relevance and accuracy.

The methodology employs the RAG framework that combines a retriever mechanism with a generative model. The retriever uses vector embeddings of hockey data to fetch relevant information based on query similarity. The generative component, powered by the Gemma-7b LLM, converts the retrieved data into coherent responses. Experimental results show that the RAG model significantly outperforms standalone LLMs, especially in delivering up-to-date and accurate answers. The Gemma-7b model, in particular, demonstrated strong performance, effectively using the contextual data provided by the retriever.

The findings illustrate the effectiveness of the RAG model in specialized information retrieval scenarios and underscore the importance of coupling precise data retrieval with sophisticated language generation. Future work may focus on further refining the retrieval processes and fine-tuning the pre-trained LLM by training it again on more similar hockey data for better results. This project highlights the potential of RAG models in transforming data retrieval for domain-specific applications.


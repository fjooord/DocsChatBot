# DocsChatBot
## Simple Implementation of making a chatbot to 'Talk' to PDFs
  - Used Langchain and Pinecone to make a simple chat bot
  - Tokenized 3 PDFs of books by David Shapiro into a pinecone vector database
  - Created a Langchain agent that when asked could search the vector database off a tokenized query of the request
  - Agent then structured response based off results received from the vector store response

# Question and Answer on your data with qdrant

Today, we will build a Question and Answer Chat Bot with knowledge from your own PDF files. We will use qdrant, a 
state-of-the-art open-source vector search engine, and OpenAI ada002 embeddings model to build out this console based 
application.

## What is qdrant?

Qdrant (read: quadrant ) is a vector similarity search engine. It provides a production-ready service with a 
convenient API to store, search, and manage points - vectors with an additional payload. Qdrant is tailored to 
extended filtering support. It makes it useful for all sorts of neural network or semantic-based matching, 
faceted search, and other applications.

Qdrant is released under the open-source Apache License 2.0. Its source code is available on [GitHub](https://github.com/qdrant/qdrant).

Our overall plan is to:
1. Create a new free qdrant cloud cluster
2. use pdfplumber to extract text from PDF and create embeddings
3. use qdrant to index the embeddings
4. use qdrant to search for the most similar embeddings based on a users input
5. Generate a response based on the most similar embedding

Check the ipynb notebook to learn more!


---

[![Artificial Intelligence Hackathons, tutorials and Boilerplates](https://storage.googleapis.com/lablab-static-eu/images/github/lablab-banner.jpg)](https://lablab.ai)




## Join the LabLab Discord


![Discord Banner 1](https://discordapp.com/api/guilds/877056448956346408/widget.png?style=banner1)  
On lablab discord, we discuss this repo and many other topics related to artificial intelligence! Checkout upcoming [Artificial Intelligence Hackathons](https://lablab.ai) Event


[![Acclerating innovation through acceleration](https://storage.googleapis.com/lablab-static-eu/images/github/nn-group-loggos.jpg)](https://newnative.ai)

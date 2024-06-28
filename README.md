Purpose: AWS Bedrock and Titan to build a smart system, like a chatbot, that understands and matches customer searches with the right products, 
making online shopping easier and more efficient.

Introduction
This guide is to learn how to use  AWS Bedrock’s Titan Embed Image model to create and compare embeddings from images and text queries. This guide matches customer text queries, like “I’m looking for a red bag” with relevant product images, showcasing AI’s power in e-commerce and digital customer experience.
The walkthrough is implemented in a Jupyter Notebook and uses AWS Bedrock and Titan Embed Image model to create and compare embeddings from images and text queries.

Steps:
1) Prerequisites: Python 3.x, Jupyter Notebook, AWS account with access to Bedrock runtime
   Python Libraries used: AWS SDK for Python (Boto3), Pandas, Sklearn (for cosine similarity), Base64, IPython

2) Setting up Jupyter Notebook
3) Creating a new product catalog, for which I have used colorful bags as catalog. Next, add all the product data to a Pandas DataFrame.
4) Next, create Embeddings from the poduct data. In the context of AI, embeddings typically refer to dense vectors that represent entities, be it words, products, or even users.
5) Now that we know what embeddings are, we can compare and measure the similarities between one of our products and what a customer is asking about through prompts.
   When we turn customer questions and product descriptions into vectors, we move into a space where we can directly compare and measure how similar items are.
6) IPython is used for rendering HTML directly in the Jupyter Notebookand therefore displaying the results.
7) Finally, there you have it, a recommendation system that compares the customer inquiry with your product catalog and gives the customer the most similar product.


# ASJOpenAILangChainQnA-
AI QnA App Based on the model given 

This is an OpenAI-based Q&A app created with LangChain MemoryVectoreStore. By providing a pdf document, chatGPT will provide responses based on that input document. We are doing vector embedding using LangChain memory vector store.

Using the LangChain pdf loader API, we can vectorize all of the text in a pdf file (in this case, I have used the Apple Watch catalog) and store it in a memory vector database. Then we can perform a similarity search and then set up the GPT model using the openAI chat completion API. This LLM GPT model job is intended to assist users by providing solutions to their questions.


Before you taking this project, you need below item to get connection with chatGPT #You need openAI account (API KEY)

1. npm install
2. create .env file and add OPENAI_API_KEY= **** Your Key ***
3. node app.js "I lost my apple watch. What I need to do next?"  / Or any question you can ask based on apple watch. I have provided the question is an argument for node js.




 

# Function Calling and RAG with Mistral 🤖📚

This project encompasses two powerful applications using Mistral AI 🤖:

1. RAG with Mistral AI:
This implementation extracts blog content 📝 from a provided URL 🌐, processes it by chunking ✂️, embedding 🔗, and storing the embeddings in a FAISS database 🗂️. The system then performs Retrieval-Augmented Generation (RAG) 📖 to retrieve relevant information from the database and generate context-aware responses.

**Key Features:**

**_RAG with Mistral AI:_**

- **URL Content Extraction 🌐📝:** Extracts the entire blog content from a provided URL.
- **Chunking and Embedding ✂️🔗:** Breaks down the content into smaller chunks, converts them into embeddings, and stores them in a FAISS database 🗂️.
- **RAG Model 📖🤖:** Performs RAG using the stored embeddings to generate responses based on the extracted blog content.

2. Function Calling with Mistral:

This part demonstrates function calling 🖱️ with Mistral AI 🤖 to interact with a database containing transaction data 💳📊. Two functions, retrieve_payment_status and retrieve_payment_dates, are used to extract specific information (payment status and payment dates) from the transaction database based on the provided query parameters.

**Key Features:**

**_Function Calling with Mistral:_**

- **Database Integration 🗄️💳:** Uses a transactional database with columns such as transaction_id, customer_id, payment_amount, payment_date, and payment_status.
- **Function Calling 🖱️📞:** Defines two functions (retrieve_payment_status and retrieve_payment_dates) to extract specific details from the database.
- **Dynamic Querying 🔄📊:** Functions are invoked dynamically to retrieve information based on transaction data.

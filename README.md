---

## **Semantic Nexus - AI-Powered Search Engine**

Semantic Nexus is an AI-powered search engine designed to provide enhanced natural language processing and domain-specific knowledge retrieval. Built with LangChain and the Hugging Face API, it offers contextual understanding and multilingual support, revolutionizing how users interact with search engines.

## **Features**
- **Contextual Understanding**: Leverages NLP models to better understand the context behind queries.
- **Multilingual Support**: Provides accurate results in multiple languages using Hugging Face models.
- **Domain-Specific Knowledge**: Retrieves focused information from domain-specific knowledge bases.

---

## **Installation**

### **Prerequisites**
- Python 3.7 or higher
- Hugging Face API key
- FastAPI
- Uvicorn

### **Clone the repository:**
```bash
git clone https://github.com/kailashkiradu/Semantic-Nexus
cd Semantic-Nexus
```

### **Install dependencies:**

### **Set up Hugging Face API credentials:**
You need to export your Hugging Face API key as an environment variable:
```bash
export HUGGINGFACEHUB_API_TOKEN='your_huggingface_api_key'
```

---

## **How to Run the Application**

1. **Start the FastAPI server**:
   Run the following command to start the server:
   ```bash
   uvicorn app:app --reload
   ```

2. **Access the application**:
   After running the above command, you can access the application in your browser at `http://127.0.0.1:8000`.

3. **Using the Search Engine**:
   - On the homepage, input natural language queries in any supported language.
   - View results processed by the Hugging Face model, tailored to the specific context and domain of the query.

---

## **How it Works**
Semantic Nexus uses a combination of **LangChain** for query understanding and **Hugging Face** models to process and retrieve results. The application is built using **FastAPI** as the backend framework, enabling efficient and fast query processing.

### **Model**
The search engine leverages the **flan-t5-xxl** model from Hugging Face, which offers advanced natural language understanding capabilities, ensuring that even complex queries are processed accurately.

### **Endpoints**
- `/`: Home page where users can input queries.
- `/search`: Processes user queries and returns contextual results.

---

## **Future Enhancements**
- **Improved Query Understanding**: Further optimization to handle more complex and technical queries.
- **Real-time Feedback**: Incorporate user feedback to continuously improve result relevance.
- **Expanded Domain Support**: Enhance the model for more industry-specific information retrieval.

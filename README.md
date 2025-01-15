# AI Travel Agent - Powered by LangGraph

Welcome to the **AI Travel Agent** project! This smart travel assistant uses LangGraph to streamline travel planning by handling tasks such as finding flights, booking hotels, and sending personalized emails. The agent interacts with users, invokes tools, and ensures a seamless travel experience.

## **Features**

- **Interactive Travel Planning**: The agent assists with travel arrangements, including flights and hotels, based on user inputs.
- **Email Integration**: Automatically generates and sends travel plans via email, with user approval.
- **Dynamic LLM Usage**: Optimizes task performance by leveraging different language models.
- **User-Friendly Interface**: Simple interaction with clear results and actionable recommendations.

## **Setup Instructions**

### Clone the Repository
```bash
git clone git@github.com:samsomsabu/Ai-Travel-Agent
cd Ai-Travel-Agent
```

### Install Dependencies

1. Ensure Python 3.11.9 is installed (if using pyenv):
   ```bash
   pyenv local 3.11.9
   ```

2. Install required packages:
   ```bash
   poetry install --sync
   ```

3. Activate the virtual environment:
   ```bash
   poetry shell
   ```

### Configure API Keys

1. Create a `.env` file in the project root directory.
2. Add the following API keys:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   SERPAPI_API_KEY=your_serpapi_api_key
   SENDGRID_API_KEY=your_sendgrid_api_key
   LANGCHAIN_API_KEY=your_langchain_api_key
   LANGCHAIN_TRACING_V2=true
   LANGCHAIN_PROJECT=ai_travel_agent
   ```
   Replace `your_openai_api_key`, `your_serpapi_api_key`, etc., with your actual keys.

## **Run the Application**

Start the chatbot with the following command:
```bash
streamlit run app.py
```

## **Usage**

Enter your travel request in the chatbot interface. For example:
> "Find flights and 4-star hotels in Amsterdam from October 1st to 7th."

The chatbot will provide detailed options with links for booking.

## **License**

This project is licensed under the MIT License. See `LICENSE.txt` for details.


# B2C-AI-Marketing-Agent

This project is an AI-powered marketing agent that generates personalized promotional emails using Cohere's language model based on customer email content. It retrieves relevant emails, processes them using NLP techniques, and crafts targeted marketing campaigns.

### Features:
- Cleans and processes customer email content for analysis.
- Uses FAISS to efficiently search and retrieve relevant emails.
- Leverages Cohere's **`command-xlarge`** model to generate personalized promotional emails.
- Supports product-specific email generation (e.g., promotions for "Body Mist").

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/b2c-ai-marketing-agent.git
   cd b2c-ai-marketing-agent
   ```
2. Set up environment variables: Create a .env file in the root of the project and add your Cohere API key:
   ```makefile
   COHERE_API_KEY=your-cohere-api-key
   ```

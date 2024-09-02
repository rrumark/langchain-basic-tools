![image](https://github.com/user-attachments/assets/ddcdbb94-4ae3-442e-8253-5379302bf39c)

LangChain Basic Tools

Project: Basic Tools

Notebook: langchain_basic_tools.ipynb

This project demonstrates how to use pre-built tools in LangChain and create an agent that can respond to user questions using those tools.

Key Components:

AzureChatOpenAI: Utilizes Azure's OpenAI API for the language model.

load_tools: Loads tools like llm-math and wikipedia.

initialize_agent: Creates an agent using the loaded tools.

Example Output:

Question: Add up the birth years of Einstein, Putin, and Vincent van Gogh.

Entering new AgentExecutor chain...

Final Answer: 5684

Finished chain.



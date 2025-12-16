## LLM Chat models

* These are language models that are specialised for Chatbot/Conversational applications. They take sequence of messages as inputs and returns chat messages as outputs 

* LLM Chat models can be Open Source / Closed Source

* The list of LLM Chat model providers can be found [here](https://docs.langchain.com/oss/python/integrations/chat/index#chat-models)

### 1.1 Open Source LLM Chat model

* These models are available at [Hugging Face](https://huggingface.co/models?pipeline_tag=text-generation&sort=trending) and **free** to use

* There are two ways to use Hugging Face models:

  * Using Hugging Face API
  
  * Downloading the model locally and use 

### 1.2 Closed Source LLM Chat model

* These models are kept in Model Provider Servers and an API key is required to access it. 

* Here four LLM chat model API calls are explored

1. Groq
2. OpenAI
3. Google Gemini
4. Mistral

### Groq

* Login & Get API Key from [Groq Console](https://console.groq.com/login?utm_source=langchain&utm_content=chat_page)

* Once you get the API key, set the **GROQ_API_KEY** in the .env file

* Groq model [list](https://console.groq.com/docs/models)

* Langchain Groq chat model documentation [link](https://docs.langchain.com/oss/python/integrations/chat/groq)


### OpenAI

* Login & Get API Key from this [link](https://platform.openai.com/api-keys)

* Once you get the API key, set the **OPENAI_API_KEY** in the .env file

* A minimum recharge of **$5** is required for using OpenAI models. [rechange link](https://platform.openai.com/settings/organization/billing/overview)

* OpenAI model list and pricing can be found [here](https://platform.openai.com/docs/pricing)

* Langchain OpenAI chat model documentation [link](https://docs.langchain.com/oss/python/integrations/chat/openai)

### Google Gemini

* Login & Get API Key from [Google AI Studio](https://ai.google.dev/gemini-api/docs/api-key)

* Once you get the API key, set the **GEMINI_API_KEY** in the .env file

* Google Gemini model [list](https://ai.google.dev/gemini-api/docs/models?authuser=1)

* Langchain Google Gemini chat model documentation [link](https://docs.langchain.com/oss/python/langchain/models#google-gemini)

### Mistral

* Login & Get API Key from [Mistral AI Studio](https://console.mistral.ai/api-keys/)

* Once you get the API key, set the **MISTRAL_API_KEY** in the .env file

* Choose a plan from this [link](https://console.mistral.ai/upgrade/plans) preferably **Experiment plan** for **free** access.

* Mistral model [list](https://docs.mistral.ai/getting-started/models)

* Langchain Mistral chat model documentation [link](https://docs.langchain.com/oss/python/integrations/chat/mistralai)

## LangSmith Tracking:

To track the LLM API calls, Check in [LangSmith](https://smith.langchain.com/)

## Notebooks:

* [01_Closed_source_llm_chat_models.ipynb](01_Closed_source_llm_chat_models.ipynb)

* [02_Open_source_llm_chat_models.ipynb](02_Open_source_llm_chat_models.ipynb)

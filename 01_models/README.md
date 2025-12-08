## Models

**Author: Abhishek Dey**

There are two categories of models in langchain

### 1. LLM Chat models

    - Input  : text
    - Output : text

### 2. Text Embedding models

    - Input  : text
    - Output : vector embeddings


## LLM Chat model

* The list of LLM Chat model providers can be found [here](https://docs.langchain.com/oss/python/integrations/chat/index#chat-models)

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


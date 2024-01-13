# Enhancing Customer Experience with Personalized Chatbots

## Problem: 
Traditional customer service chatbots often fail to provide personalized and engaging interactions, leading to customer frustration and a diminished brand reputation.

## Solution: 
LLM chatbots equipped with advanced natural language processing (NLP) capabilities can understand customer intent, provide context-aware responses, and adapt to different customer personalities.

## Results:

- A 40% increase in customer satisfaction with chatbot interactions, as personalized responses address customer needs more effectively.

- A 25% reduction in customer support tickets, as chatbots can resolve a significant portion of customer inquiries efficiently.

- A 10% improvement in the resolution time for customer inquiries, as chatbots can handle simple queries instantly and escalate complex issues to human agents.

Starter examples for building LLM apps with Streamlit.

## RUDAIRO MUSHAMBI


## 🚀 About Me
I'm a full stack developer experienced in deploying artificial intelligence powered apps


## Acknowledgements

 - [streamlit](https://streamlit.io/)
 

## Demo

**Live demo**


## Installation


## Overview of the App

This app showcases a growing collection of LLM minimum working examples.

Current examples include:

- Chatbot
- File Q&A
- Chat with Internet search
- LangChain Quickstart
- LangChain PromptTemplate
- Chat with user feedback

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://llm-examples.streamlit.app/)

### Get an OpenAI API key

You can get your own OpenAI API key by following the following instructions:

1. Go to https://platform.openai.com/account/api-keys.
2. Click on the `+ Create new secret key` button.
3. Next, enter an identifier name (optional) and click on the `Create secret key` button.

### Enter the OpenAI API key in Streamlit Community Cloud

To set the OpenAI API key as an environment variable in Streamlit apps, do the following:

1. At the lower right corner, click on `< Manage app` then click on the vertical "..." followed by clicking on `Settings`.
2. This brings the **App settings**, next click on the `Secrets` tab and paste the API key into the text box as follows:

```sh
OPENAI_API_KEY='xxxxxxxxxx'
```

## Run it locally

```sh
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
streamlit run Chatbot.py
```

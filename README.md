# **ShownetAI**

### Analyze Your Favorite Series with NLP

In this project, we analyze TV series using advanced Natural Language Processing (NLP) and Large Language Models (LLMs). We start by scraping a custom dataset, then move to building several models to classify themes, create a character network, and develop a chatbot that interacts with characters from the series. Finally, all of this is packaged into a user-friendly web interface using Gradio.

## **Overview**

This project contains five main components, each housed in its respective folder:

- **crawler**: Web scraping using Scrapy to build a dataset.
- **character_network**: Create a character relationship network using SpaCy’s NER, NetworkX, and PyViz.
- **text_classifier**: Train a custom text classifier using LLMs.
- **theme_classifier**: Extract the main themes of the series using Zero-shot classifiers.
- **character_chat_bot**: Develop a chatbot to chat with characters using LLMs.

## **Tech Stack**

- **Scrapy**: For web scraping and dataset collection.
- **SpaCy**: For Named Entity Recognition (NER).
- **NetworkX & PyViz**: For building and visualizing character networks.
- **Hugging Face Transformers**: For implementing LLM-based theme and text classifiers.
- **Gradio**: For creating a web-based GUI for seamless interaction.

## **Requirements**

Before running the project, install the necessary dependencies by running:

```bash
pip install -r requirements.txt

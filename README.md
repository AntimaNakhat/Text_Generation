# Text Generation using Google's Gemini Pro

This repository demonstrates how to generate text using the **Gemini Pro** model via the Google Generative AI SDK. The project is implemented in a Jupyter Notebook and provides a simple interface for interacting with Gemini's large language model (LLM).

## 🚀 Features

- Text generation with Google's Gemini Pro model
- Interactive inputs through a notebook environment
- Simple, minimal setup for testing Gemini capabilities
- Built using Python and Google's `google-generativeai` library


## 🛠️ Requirements

- Python 3.7+
- Google Generative AI SDK (`google-generativeai`)
- A valid Google API Key with access to Gemini models

## 🔧 Setup Instructions

1. **Clone the Repository:**

```git clone https://github.com/AntimaNakhat/Text_Generation.git```
```cd Text_Generation```

2. **Install Dependencies:**

Make sure you have pip installed and run:

```pip install google-generativeai```

3. **Set Up API Key:**

Get your API key from Google AI Studio and configure it:

```import os```
```os.environ["GOOGLE_API_KEY"] = "your-api-key-here" ```

You can also use a .env file or other secrets management for production use.

**📌 Notes**

Ensure your API key has access to Gemini Pro.

The notebook is designed for educational and testing purposes.

Text generation quality may vary based on the prompt

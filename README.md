# AI_RESEARCH_ASSISTANT  
*Transforming research into insights, effortlessly and efficiently.*

![last-commit](https://img.shields.io/github/last-commit/WaleedMuslem/ai_research_assistant?style=flat&logo=git&logoColor=white&color=0080ff)
![repo-top-language](https://img.shields.io/github/languages/top/WaleedMuslem/ai_research_assistant?style=flat&color=0080ff)
![repo-language-count](https://img.shields.io/github/languages/count/WaleedMuslem/ai_research_assistant?style=flat&color=0080ff)

*Built with the tools and technologies:*  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B.svg?style=flat&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?style=flat&logo=OpenAI&logoColor=white)

---

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)

---

## Overview
**ai_research_assistant** is a powerful developer tool designed to enhance research efficiency by facilitating the analysis of various document formats, including PDF and DOCX.

**Why ai_research_assistant?**

This project streamlines the research process by leveraging AI to extract insights and summaries from documents. The core features include:
- 📄 **Document Upload Support:** Easily upload and analyze documents in multiple formats.
- 🤖 **AI Insights:** Gain valuable insights and summaries powered by advanced AI models.
- 🔍 **Comparative Analysis:** Compare findings across multiple documents for comprehensive research.
- 🌐 **User-Friendly Interface:** Built with Streamlit, ensuring an interactive and intuitive user experience.
- 📊 **Robust Dependency Management:** Seamlessly integrates essential libraries for optimal functionality.

---

## Getting Started

### Prerequisites
This project requires the following dependencies:
- **Programming Language:** Python
- **Package Manager:** Pip

### Installation
Build ai_research_assistant from the source and install dependencies:

1. **Clone the repository:**
   ```sh
   ❯ git clone https://github.com/WaleedMuslem/ai_research_assistant

2. **Navigate to the project directory:**
   ```sh
   ❯ cd ai_research_assistant

3. **Install the dependencies:**
   ```sh
   ❯ pip install -r requirements.txt

### Usage
1. **Run Ollama Locally:**  
Ensure Ollama is installed and running the model `deepseek-r1:1.5b`.

   ```sh
   > ollama pull deepseek-r1:1.5b
   > ollama run deepseek-r1:1.5b

2. **Run the Streamlit App:**  

   ```sh
   > streamlit run research_assist.py

3. Use the Web Interface  
Open the app in your browser.

Upload `.pdf`, `.docx`, or `.txt` files from the sidebar.

Enter your research question in the text area.

Click `Analyze`.

Explore the results in three tabs:

- **Main Analysis** – Direct response to your question.
- **Key Points** – Highlights and important details.
- **Summary** – A concise overview of the document.

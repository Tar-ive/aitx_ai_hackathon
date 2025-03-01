# SupplyDoom: AI-Powered Compliance Chatbot

<a href="https://colab.research.google.com/github/Tar-ive/aitx_ai_hackathon/blob/main/bounter.ipynb" target="_parent">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Overview
This is an AI-powered chatbot designed to assist exporters in complying with FDA regulations. It converts natural language queries into SQL commands, retrieves relevant compliance information, and provides real-time assistance. Built using LlamaStack and Together AI, it integrates tools for database interaction, rule interpretation, and user-friendly UI components using Replit.

## Features
- **AI-Powered Compliance Chatbot**: Answers user queries about FDA regulations and requirements with simplified responses.
- **Text-to-SQL Conversion**: Uses LlamaStack and Together AI to generate SQL queries from user input.
- **Database Schema Exploration**: Extracts and processes metadata from regulatory databases.
- **FDA Accessibility Agent**: Assists exporters in understanding and following FDA compliance rules.
- **Session Management**: Tracks query history and user interactions.
- **Interactive UI**: Provides an easy-to-use interface for real-time responses.

## Installation
Ensure you have the required dependencies installed:
```bash
pip install llamastack together 
```

## Usage
Run the following command to start the chatbot interface:
```bash
python app.py
```

Or open the notebook in Google Colab and execute the cells step by step.

## Project Structure
```
├── bounter.ipynb       # Jupyter Notebook with development and testing
├── app.py              # Main script to launch the chatbot UI
├── requirements.txt    # List of dependencies
└── README.md           # Project documentation
```

## Future Improvements
- Enhance SQL execution handling to improve error detection.
- Expand regulatory database support for broader compliance coverage.
- Improve UI design with more interactive elements.
- Integrate additional AI models for better response accuracy.

## Contributors
- **Saksham Adhikari** (Lead Developer)
- [Kusum Bhattarai Sharma, Raghav Ojha, Marie Vargaz, Connor Burgess , Ajay Bethireddy]

## License
This project is licensed under the MIT License.


# ChatPi

ChatPi is a simple chatbot implementation for Raspberry Pi using OpenAI's GPT-3.5 model.

## Authors

- CEO: Rodolfo Lopez
- PM: Kera Hernandez
- Dev0: Nate Spinks
- Dev1: Michael Gallagher
- Test: Lucca Fabani

## Date

5/5/23

## Overview

This project demonstrates how to run a chatbot on a Raspberry Pi using Python and the OpenAI API. It was developed as a student project to explore AI integration on embedded systems.

## Features

- Utilizes OpenAI's GPT-3.5 model (text-davinci-003)
- Runs on Raspberry Pi with Raspberry Pi OS
- Implements a simple command-line interface for user interaction
- Tracks and displays token usage for each query

## Prerequisites

- Raspberry Pi with Raspberry Pi OS installed
- Python 3.x
- OpenAI API key

## Installation

1. Clone this repository to your Raspberry Pi.
2. Install required dependencies:
   ```
   pip install openai python-dotenv
   ```
3. Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

## Usage

Run the script using Python:

```
python chat_pi.py
```

Enter your questions when prompted. Type 'q', 'Q', 'quit', 'QUIT', or 'EXIT' to end the chat session.

## Notes

- The chatbot performs best with clearly defined questions.
- Token usage is displayed after each response to help manage API costs.
- The temperature setting (0.5) balances creativity and accuracy in responses.

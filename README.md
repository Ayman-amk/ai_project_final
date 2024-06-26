﻿# For Rasa Chatbot Project

### Folder name: 2nd

## Overview

This project is a chatbot developed using the Rasa framework. Rasa is an open-source natural language processing framework for building conversational AI applications.

## Features

- **Natural Language Understanding (NLU):** Utilizes machine learning models to understand user inputs and extract relevant information.
- **Dialogue Management:** Implements dialogue flow and logic to provide meaningful responses to user queries.
- **Custom Actions:** Supports custom actions to perform specific tasks or interact with external systems.
- **Integration:** Can be integrated with various channels such as Slack, Facebook Messenger, or custom web interfaces.
- **Training Data:** Includes annotated training data for NLU and dialogue management models.

## Setup

1. **Install Dependencies:** Ensure you have Python and pip installed. Then, install the required dependencies by running:

```bash
  pip install rasa
  pip install spacy
  python -m spacy download en_core_web_md
```

2. **Training the Model:** Train the NLU and dialogue management models by running:

```bash
  rasa train
```

3. **Run the Chatbot:** Once the models are trained, start the chatbot server by running:

```bash
  rasa run
```

4. **Interact with the Chatbot:** Open your web browser and navigate to `http://localhost:5005` to interact with the chatbot.

5. **Start talking with the chatbot:** example :

```bash
  What is IoT?
```

## Usage

- **Training Data:** Modify the training data in the `data` directory to improve the chatbot's performance.
- **Custom Actions:** Implement custom actions in the `actions.py` file to extend the functionality of the chatbot.
- **Integration:** Integrate the chatbot with your preferred messaging platform by following the Rasa integration guides.
- **Stop the chatbot:** by typing

```bash
  /stop
```

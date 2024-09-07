# Rasa Chatbot

This project showcases a conversational AI bot built using Rasa, an open-source framework for building chatbots and virtual assistants.

## Features

- **Natural Language Understanding (NLU)**: Understand user intents and extract relevant entities from user input.
- **Dialogue Management**: Handle conversations and maintain context using Rasa's dialogue management capabilities.
- **Custom Actions**: Implement custom actions to perform tasks or retrieve information based on user queries.
- **Interactive Stories**: Design complex conversation flows with Rasa’s story-based training.

## Configuration

1. **Update config.yml:** Customize the Rasa configuration file as needed for your project. This file contains settings for NLU and dialogue management.
2. **Train the Model**
   ```bash
   rasa train
3. **Start the Rasa Server**
   ```bash
   rasa run
4. **Start the Action Server (if applicable)**
   ```bash
   rasa run actions
5. **Test the Chatbot**
   ```bash
   rasa shell



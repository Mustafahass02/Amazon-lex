# Amazon-lex
🤖 Amazon Lex Chatbot Project

This project demonstrates how to build and configure a chatbot using Amazon Lex, AWS's service for building conversational interfaces. The chatbot includes a welcome intent and a fallback intent to handle user interactions effectively.

📁 Project Overview

Platform: Amazon Lex (AWS)
Language: English (US)
Confidence Threshold: 0.40
Key Features:

Custom Welcome Intent
Fallback Intent for unrecognized inputs
Basic IAM role for Lambda integration
🛠️ Implementation Steps

1. Bot Creation

Built from scratch using Amazon Lex
Setup completed in under 5 minutes
2. IAM Configuration

Created a role with basic permissions to allow Lex to interact with other AWS services (e.g., AWS Lambda)
3. Confidence Settings

Used the default confidence score of 0.40 for intent classification
This means the bot needs at least 40% confidence to respond to user inputs
4. Intent Design

WelcomeIntent: Greets users with messages like "Hi", "Hello", and "I need your help"
FallbackIntent: Handles unrecognized user inputs with clear error messages
🧪 Testing Results

The chatbot was successfully tested with:

✅ Recognized inputs: "Hi", "Hello", "I need your help"
❌ Unrecognized inputs: Trigger FallbackIntent with message 'Intent FallbackIntent is fulfilled'
🔁 Fallback Handling

The FallbackIntent is automatically triggered when the bot's confidence is below the set threshold. This was customized to improve user experience by clearly communicating when the bot doesn't understand a request.

🕒 Project Duration

This project was completed quickly, highlighting Amazon Lex's ease of use and rapid deployment capabilities.

👨‍💻 Author
Mustafa Hassan

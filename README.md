
# 🤖 Customer Support Chatbot

## Project Overview

This project involves the creation of a simple yet effective customer support chatbot designed to assist users with common queries and provide instant 24/7 support. Built entirely using Google's **Dialogflow ES** (Essential/Standard Edition), this chatbot demonstrates core conversational AI principles, including intent recognition, entity extraction, and automated responses, all without writing a single line of code.

The primary goal of this chatbot is to automate responses to Frequently Asked Questions (FAQs), handle greetings gracefully, and provide a polite fallback message when it doesn't understand a user's input. The chatbot's knowledge base was enriched by leveraging a real-world customer support chat dataset.

This project was completed as part of Machine Learning Task 3 for  Future Interns Program.

## ✨ Features

  * **Intelligent Greetings:** Responds warmly to user greetings.
  * **FAQ Answering:** Provides accurate answers to predefined common customer support questions (e.g., "Where is my order?", "How to return an item?").
  * **Smart Fallback:** Offers helpful suggestions when it cannot understand a query, guiding the user towards relevant topics.
  * **Knowledge Base Enhancement:** Training phrases were developed and refined using examples from a customer support chat dataset (from Kaggle).
  * **Telegram Integration:** Successfully deployed and tested the chatbot directly on the Telegram messaging platform.

## 🛠️ Technologies Used

  * **Dialogflow ES (Essential/Standard Edition):** The sole platform used for designing the conversational flow, defining intents, managing responses, and testing the chatbot. This project leveraged its drag-and-drop, no-code interface extensively.
  * **Telegram Bot API:** Used for connecting and deploying the chatbot to the Telegram messaging platform.
  * **Customer Support Chat Dataset (Kaggle):** Utilized to gather realistic examples for training phrases and improve the chatbot's understanding of various customer queries.

## 🚀 Getting Started (How to Explore/Replicate)

To understand how this chatbot was built and to test its capabilities, follow these steps:

### 1\. Dialogflow Agent Setup

The core of this chatbot resides in a Dialogflow ES agent.

1.  **Access the Dialogflow ES Console:**

      * Go to the [Dialogflow ES Console](https://dialogflow.cloud.google.com/).
      * Sign in with your Google Account.
      * (Optional: If you want to replicate this, you would create a new agent and manually set up the intents as described below.)

2.  **Key Intents Implemented:**

      * **`Default Welcome Intent`**: Modified to provide a welcoming and helpful greeting to users.
      * **`Default Fallback Intent`**: Configured to deliver polite and guiding messages when the chatbot doesn't understand the user's input.
      * **Custom FAQ Intents**: Multiple custom intents were created for common customer support queries, such as:
          * `CheckOrderStatus` (e.g., "Where is my order?", "Track my delivery")
          * `ReturnItem` (e.g., "How do I return something?", "Return policy")
          * `ContactSupport` (e.g., "I need to speak to someone", "Customer service number")
          * *(Add more specific examples if you remember other key intents you created)*
            Each custom intent includes diverse "Training Phrases" (inspired by the Kaggle dataset) and specific "Responses" tailored to answer the query.

3.  **Training Data Source:**

      * The "Customer Support Chat Dataset" from Kaggle was instrumental in populating the "Training Phrases" for the custom FAQ intents, making the chatbot more robust in understanding natural language variations.

4.  **Test the Chatbot within Dialogflow:**

      * The "Try it now" simulator on the right side of the Dialogflow console was used extensively to test the chatbot's responses and fine-tune intent recognition.

### 2\. Telegram Integration

The chatbot was successfully deployed and tested live on Telegram.

1.  **Connect in Dialogflow:**
      * In the Dialogflow agent, the "Telegram" integration was enabled by providing the API token obtained from Telegram's `@BotFather`.
2.  **Interact on Telegram:**
      * The chatbot is accessible by searching for its unique username (e.g., `@your_bot_username`) directly within the Telegram app.
      * Users can initiate a conversation with `/start` and then ask questions to receive automated support.


## 🧠 Skills Learned

Through this project, I gained practical experience in:

  * **Chatbot Fundamentals:** Understanding the basic architecture and workflow of conversational AI agents in a no-code environment.
  * **Conversational Design:** Crafting engaging greetings, informative responses, and effective fallback strategies for real-world interactions.
  * **Natural Language Understanding (NLU):** Learning how AI platforms like Dialogflow interpret user intent from diverse phrasing and leveraging external datasets for better training.
  * **Platform Integration:** Successfully connecting and deploying a chatbot to a popular messaging platform (Telegram) using a no-code approach.
  * **Practical Application:** Applying theoretical knowledge of machine learning concepts (like intent classification) to build a functional tool.

## 📞 Contact

  * **Project Link:**(https://www.google.com/search?q=https://github.com/Snehal977/FUTURE_ML_03)


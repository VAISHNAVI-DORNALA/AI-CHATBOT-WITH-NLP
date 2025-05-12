# AI-CHATBOT-WITH-NLP

"COMPANY" : CODETECH IT SOLUTIONS

"NAME" DORNALA VAISHNAVI REDDY

"INTERN ID" : CT06DK637

"DOMAIN" : Python Programming.

"DURATION" : 6 WEEKS

"MENTOR" : NEELA SANTOSH

##Project Overview: Rule-Based NLP Chatbot Using NLTK
This task demonstrates the development of a basic rule-based text chatbot using Python and the Natural Language Toolkit (NLTK) library. The chatbot is capable of recognizing simple intents such as greetings, farewells, and expressions of gratitude, and responding accordingly. The chatbot runs in a command-line interface and can carry on a basic conversation loop with the user until a termination phrase (like "bye") is detected.

Tools and Technologies Used
Python: The programming language used for building the chatbot due to its simplicity and extensive support for Natural Language Processing (NLP) through libraries like NLTK.

NLTK (Natural Language Toolkit): A powerful NLP library in Python, used here for:

Tokenization (word_tokenize) to break input into words.

Stopword Removal using a pre-defined list of common words (like “is”, “and”, “the”) that are filtered out to focus on meaningful keywords.

Punctuation Filtering to remove special characters for cleaner token processing.

Random: Python’s built-in module is used to randomly select a response from the predefined list to make the chatbot feel more dynamic and less repetitive.

String: Provides punctuation constants used to filter out punctuation during preprocessing.

How the Chatbot Works
Initialization:

The chatbot defines a knowledge base with categorized responses: greetings, goodbyes, thanks, and a default fallback.

Predefined keyword lists are used to identify user intent based on specific words like "hello", "bye", or "thanks".

Preprocessing:

When a user enters a message, it is first converted to lowercase to standardize input.

Tokenization splits the sentence into individual words.

Stopwords and punctuation are removed to retain only significant keywords.

Intent Matching:

The processed tokens are compared with the predefined keyword lists.

If any keywords match a specific category (e.g., greetings), the bot selects an appropriate response from that category.

If no keywords match, a default message is returned.

Conversation Loop:

The chatbot runs in an infinite loop, processing user input and providing responses.

The loop breaks when a goodbye phrase is detected.

Applications of This Task
While this chatbot is simple, the structure and concepts behind it have many real-world applications:

Customer Support Bots: Can be used for answering frequently asked questions in a customer service environment.

Educational Tools: Helps students interactively learn topics via Q&A format.

Virtual Assistants: Acts as a basic layer of interaction in larger systems like booking apps or helpdesk tools.

Prototyping and Training: Ideal for testing conversation logic before integrating with more advanced AI/ML models.

Limitations and Future Enhancements
This chatbot uses static keyword matching, which limits its understanding of varied or complex user inputs.

It lacks context-awareness and memory, making multi-turn conversations difficult.

A future upgrade could include:

Machine Learning models for dynamic intent recognition.

Integration with NLU platforms like Rasa or Dialogflow.

Addition of context handling and user personalization.

Conclusion
This chatbot project is an excellent entry-level application of Natural Language Processing. It introduces fundamental techniques like tokenization, stopword filtering, and intent classification using rule-based methods. Despite its simplicity, it serves as a foundational model for building more sophisticated conversational agents using NLP and AI.

##OUTPUT

![Image](https://github.com/user-attachments/assets/97a61205-8d54-4bf3-b85b-afec58c976f4)

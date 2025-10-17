End-to-End AI Customer Service Assistant

This project demonstrates a complete conversational AI pipeline for a customer service assistant that integrates moderation, product intelligence, and self-evaluation into one seamless flow.
It combines OpenAI’s GPT models with real-time data retrieval and interactive UI elements to deliver a safe, helpful, and adaptive customer experience.

🚀 Features

Input Moderation: Automatically screens all user messages and AI outputs for safety using the OpenAI Moderation API.

Intelligent Product Recognition: Extracts product names and categories from user input using a custom utility pipeline.

Dynamic Product Information Lookup: Retrieves and formats relevant product details before responding.

Conversational Response Generation: GPT produces friendly, concise, and context-aware customer support replies.

Self-Evaluation Loop: The model rechecks its own responses for accuracy and completeness before sending them.

Escalation Handling: Automatically routes uncertain cases to human support.

Interactive Chat Interface: Built with Panel, providing a real-time conversational dashboard.

⚙️ Tech Stack

Python

OpenAI API (ChatCompletion + Moderation)

Panel for the GUI interface

dotenv for secure API key management

Custom utility functions for product categorization and lookup

🧩 System Flow

User enters a query about products.

System moderates input → extracts product context → fetches details.

GPT composes a response using structured data.

Response is moderated and self-checked for quality.

Assistant interacts continuously via a web-based chat panel.
Run (Python 3.11):
-> pip install openai panel python-dotenv
-> pip install utils
-> pip install --upgrade panel bokeh
-> pip install panel==1.3.1 bokeh==3.5.1
-> pip install panel


💡 Vision

An intelligent, safe, and self-evaluating digital assistant that blends human empathy with AI precision — a foundation for next-generation autonomous customer experience systems.


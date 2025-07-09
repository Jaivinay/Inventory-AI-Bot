🤖 AI Inventory Assistant Bot (Built with Botpress)
This project is an AI-powered support bot developed using Botpress, designed to assist with answering inventory-related questions based on structured business data. It provides users with fast, accurate responses related to inventory levels, stock gaps, and reorder points.

📌 Purpose
The goal is to simulate a customer or business-facing assistant that interacts with a dataset and helps answer questions such as:

Which items are low in stock?

What is the current stock of a particular item?

Which item is closest to its reorder point?

It demonstrates how conversational AI can be integrated into decision-support systems using low-code platforms.

📊 Dataset & Analysis Focus
The dataset used includes inventory fields such as:

Item Number

Description

Quantity on Hand

Reorder Point

Gap to Reorder

The assigned analysis question was:

What are the top 10 inventory items closest to their reorder point?

This was calculated using a simple gap formula:

text
Copy
Edit
Gap = Quantity on Hand - Reorder Point
The lower the gap, the closer the item is to needing reorder.

🛠️ Bot Architecture
Start Node: Welcomes the user and guides the conversation.

Autonomous Node: Handles knowledge-based responses using the connected dataset.

Knowledge Base: Built from a .csv file containing filtered inventory data (10 rows).

Instructions: The bot responds in a friendly, helpful tone and only based on the available data.

💬 Sample Questions to Try
"Which item is closest to reorder?"

"What is the stock for item 77?"

"Show the reorder point for item Y3"

"How much quantity is available for item 113?"

🌐 Deployment
The bot is embedded in a custom HTML webpage (mybot.html)

Hosted on a university web server via myweb.usf.edu

Fully responsive and includes instructions, summary, and live chatbot

✅ Deliverables
SQL Query (.sql)

CSV Data File (.csv)

Webpage (mybot.html) with embedded chatbot

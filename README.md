# 🧠 AI Inventory Assistant Bot

This project demonstrates an AI chatbot built using **Botpress**, deployed via a custom HTML webpage. The chatbot helps answer inventory-related questions using a small dataset focused on item stock and reorder information.

---

## 🔍 Analysis Question

**What are the top 10 inventory items closest to their reorder point?**  
This bot helps identify items nearing restock thresholds to improve inventory decisions.

---

## 📁 Dataset Details

- Format: CSV (10 rows)  
- Columns:  
  - Item Number  
  - Description  
  - Quantity on Hand  
  - Reorder Point  
  - Gap to Reorder  

This data was uploaded into a Botpress Table and used to build the bot's Knowledge Base.

---

## 💬 Example Questions

- "Which item is closest to reorder?"  
- "Show stock for item 77"  
- "What is the reorder point of Y3?"

The bot can understand both short and detailed questions from users.

---

## 🌐 Live Demo

🧪 You can interact with the deployed bot here:  
**[http://myweb.usf.edu/~jaivinaygudiveka/mybot.html](http://myweb.usf.edu/~jaivinaygudiveka/mybot.html)**

---

## 🚀 Tech Stack

- Botpress Cloud (Bot creation, Knowledge Base, Hosting)
- HTML/CSS (Web page interface)
- SQLite (for original SQL query)
- DB Browser for SQLite (CSV export)
- Cyberduck (for FTP upload)

---

## 📌 Notes

- This chatbot was designed to be simple and user-friendly.
- Users are greeted automatically and guided to ask inventory-related questions.
- The project is suitable for business users monitoring stock levels.

---

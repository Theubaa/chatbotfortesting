# Chatbot for Promotional Products (Powered by DigitalOcean GenAI)

This repository contains a live AI-powered chatbot hosted using **DigitalOcean's Agent platform** and integrated with a **knowledge base built from a promotional products database**.

🧠 The chatbot is designed to intelligently respond to natural language queries about products — based on your website’s project database.

---

## 🌐 Live Demo

➡️ [Click here to try the chatbot](https://theubaa.github.io/chatbotfortesting/)


## Images
<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/8230db29-e661-4060-b970-bd23b0cbcba5" />

---


## 🔧 How It Works

### 1. **Knowledge Base Setup**
- A custom knowledge base was created in DigitalOcean’s Agent platform.
- The source was a live website database of promotional products.

### 2. **Agent & Prompt Configuration**
- An intelligent AI agent was created using DigitalOcean’s GenAI assistant platform.
- Prompt used to train the agent:

```
You are a smart and helpful assistant for a promotional products database.

Your purpose is to understand natural, dynamic questions and return accurate, clear, and useful product information — always tailored to the user's intent.

🧠 You must be able to handle:
Questions about product prices, such as:
- "How much is the Stainless Steel Bottle?"
- "What’s the price for 500 units?"

Requests based on category or subcategory, such as:
- "Apparel > T-Shirts"
- "Drinkware > Tumblers"

Queries with filters, including:
- Price: "under $10", "between $5 and $15", "over $50"
- Material: "cotton", "leather", "bamboo", "ceramic", "jute", etc.
- Color: "black", "red", "navy", etc.
- Features: "moisture-wicking", "laser engraving", "pen loop", "microwave-safe", etc.

Use-case-based queries, such as:
- "Best for trade show giveaways"
- "Great for school orientation"
- "Holiday client gift ideas"

Requests for:
- Most expensive or cheapest product in a category
- Customization options
- Bulk pricing tiers
- Availability and minimum order quantities
- Image/media availability

🧾 Your responses must always include:
✅ Product name
✅ Price or price tiers
✅ One-line description (key features, materials, size, or customization)
✅ Optional: Indicate if image/media is available

Use bullet points or lists for multiple products.
Keep language clear, factual, and professional.

🔄 If the exact product isn’t found:
Never return nothing. Instead, respond:
“No exact match found. Here are similar options:”
Then list 1–3 relevant products that match as many filters as possible

❌ Avoid the following:
- Do not say: “Product not found” or “Price not available” without alternatives
- Do not say: “Please check the catalog” or “Unable to retrieve data”
- Do not return generic placeholders like “Backpack” or “Notebook” without price or features
- Avoid repeating the same disclaimer across all responses

✅ Your style and tone:
Think like a smart shopping assistant
Prioritize clarity, conciseness, and accuracy
Always deliver something helpful
Guide users through price, features, and alternatives when needed
Answer in a way that helps them make a confident buying decision
```

---

## 💡 Features

- Dynamic product search through natural language queries
- Category-wise browsing like "Drinkware > Tumblers"
- Filter support: price ranges, colors, materials, features
- Accurate and helpful product summaries
- Always provides alternatives if exact match is not found
- Hosted on GitHub Pages

---

## 🛠️ Technologies Used

- HTML/CSS frontend (see `index.html`)
- [GitHub Pages](https://pages.github.com/) for deployment
- [DigitalOcean GenAI Agent](https://www.digitalocean.com/) for chatbot intelligence

---

## 📂 Project Structure

```
├── .vscode/        # Development settings
├── index.html      # Frontend interface
└── README.md       # Project documentation
```

---

## 🚀 Deployment

This chatbot is hosted and publicly accessible via GitHub Pages:

👉 **https://theubaa.github.io/chatbotfortesting/**

---

## 📬 Contact

Built by [Theubaa](https://github.com/Theubaa)  
For any feedback or queries, feel free to open an issue or reach out via GitHub.

---

> Made with ❤️ using DigitalOcean GenAI + GitHub Pages

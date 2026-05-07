🚀 Overview

Choosing what to eat can be difficult—especially when dealing with unfamiliar dishes or food allergies.
This project solves that by providing an intelligent assistant that:

📖 Reads and understands restaurant menus (PDF or database)
🍽️ Recommends dishes based on user preferences
⚠️ Identifies potential allergens in food items
🧠 Explains dishes in simple, user-friendly language
✨ Features
📋 Menu Parsing
Extracts dish names, ingredients, and descriptions from menu PDFs or structured data.
🥗 Personalized Recommendations
Suggests dishes based on:
Vegetarian / Vegan preferences
Spicy / Mild taste
User input queries
⚠️ Allergy Detection
Helps users avoid ingredients they are allergic to:
Nuts
Dairy
Gluten
Shellfish
Highlights risky dishes and suggests safer alternatives.
🧾 Dish Explanation
Breaks down complex dish names into:
Ingredients
Cooking style
Flavor profile
💬 Conversational Interface

Users can interact naturally:

“What should I eat if I’m vegetarian and allergic to nuts?”

🛠️ Tech Stack
LangChain – LLM-based workflow and tool integration
LangGraph – Multi-step agent orchestration
Streamlit – Interactive web interface
Python – Backend logic
PDF/Text processing tools – Menu ingestion
📂 Project Workflow
User Query
   ↓
Intent Understanding
   ↓
Menu Parsing (PDF/DB)
   ↓
Allergy + Preference Filtering
   ↓
Recommendation Engine
   ↓
Response with Explanation
💡 Example Interaction

User:

I’m vegetarian, like spicy food, and allergic to nuts

Agent:

Here are some safe and suitable options:

Chili Paneer 🌶️ – Spicy paneer dish without nuts
Spicy Veg Noodles 🌶️ – Stir-fried noodles with chili sauce
Vegetable Biryani – Flavorful rice dish (ensure no nut garnish)

⚠️ Avoid: Dishes containing cashews or nut-based gravies

⚠️ Disclaimer

This agent provides guidance based on available menu data.
Users with severe allergies should always confirm with the restaurant staff before ordering.

🔮 Future Improvements
🔗 Integration with live restaurant APIs
🌍 Multi-language support
🎤 Voice-based interaction
🧮 Nutritional and calorie analysis
📌 Use Case

This project demonstrates how AI can:

Improve dining experiences
Enhance accessibility for people with dietary restrictions
Provide intelligent, personalized recommendations
🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

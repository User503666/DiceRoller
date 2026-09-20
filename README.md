🎲 Roll for Dinner: D&D Meal Decider

A tabletop RPG-themed interactive web application designed to help indecisive adventurers answer the ultimate quest prompt: "What should we eat tonight?"

📜 Table of Contents

Features

Tech Stack

Getting Started

How It Works

Customization

Contributing

License

✨ Features

D20 Meal Rolling: Click to roll a 20-sided die with randomized animations and sound effects to select your meal category or specific dish.

Critical Hits & Fumbles:

🎯 Nat 20: Treats you to a legendary feast, takeout splurges, or your absolute favorite dish!

💥 Nat 1: Forces you into "Rations Mode" (leftovers, instant ramen, or whatever is in the back of the pantry).

Customizable Tables: Add, edit, or remove meals to tailor the roll tables to your local restaurants or personal recipes.

Filter by Dietary Restrictions: Quick toggles for Vegetarian, Vegan, Gluten-Free, and Quick Prep (< 20 mins) options.

Immersive D&D Theme: Styled with parchment textures, fantasy typography, and playful RPG flavor text.

🛠️ Tech Stack

Frontend: HTML5, Tailwind CSS / Custom CSS, JavaScript (ES6+)

Icons & Graphics: FontAwesome / Lucide Icons

Audio: Web Audio API / HTML5 Audio for dice-rolling SFX

🚀 Getting Started

Prerequisites

All you need is a modern web browser! No complex backend server is required.

Installation

Clone the repository:

git clone https://github.com/your-username/roll-for-dinner.git


Navigate to the project directory:

cd roll-for-dinner


Open the app:
Simply double-click index.html or open it in your browser of choice.

🎮 How It Works

Select your filters (optional): Choose dietary constraints or budget ranges.

Hit "Roll for Initiative": Watch the D20 spin and calculate your outcome.

Accept Your Fate:

Accept the result and get cooking/ordering.

Use your once-per-day "Heroic Inspiration" re-roll if you disagree with the dice gods.

🎨 Customization

You can easily modify the meal tables by updating the core JSON array in app.js or via the in-app settings modal:

[
  { "id": 1, "name": "Dragon's Breath Tacos", "category": "Mexican", "prepTime": "15 mins", "isTakeout": true },
  { "id": 2, "name": "Elven Waybread (Artisan Sandwich)", "category": "Quick Prep", "prepTime": "10 mins", "isTakeout": false }
]


🤝 Contributing

Contributions are welcome! If you'd like to add new features, fix bugs, or improve the UI/UX:

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git checkout -b feature/AmazingFeature)

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for more information.

May your rolls be high and your meals delicious! 🗡️🍲

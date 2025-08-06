🧑‍🍳 Food Recipe Web App (Food Recipes)
This is a responsive and interactive React-based food recipe application that displays a list of pizza recipes. It allows users to explore various recipes and view detailed ingredients and step-by-step instructions. The data is dynamically fetched from the Spoonacular API, and each recipe page is rendered in real-time based on user interaction.

🧰 Tech Stack
Category	Technology
Framework	React.js
Styling	CSS Modules
State Management	useState, useEffect
Routing	Props-based dynamic rendering (can be extended using React Router)
Data Source	Spoonacular Food API
Component Structure	Modular (e.g., FoodDetails, ItemList)
Deployment Ready	✅ Yes 

🔧 Features & Implementation Details
1. 🍕 Recipe List Panel (Left Sidebar)
A scrollable list of recipe cards with:

📸 Thumbnail image

📋 Title

👆 "View Recipe" button

Built using .map() over a recipe array or mock data.

Clicking a card updates the selected recipe using foodId.

2. 📄 Recipe Detail Panel (Main Section)
Displays full recipe info:

🖼 Image

⏱ Prep time

🍽 Servings

🌿 Vegetarian/Vegan indicators

💲 Price per serving

Ingredient list rendered using a child component (ItemList).

Cooking instructions displayed in ordered list format.

3. 🔁 Dynamic API Fetching
Uses Spoonacular's recipe API endpoint:

https://api.spoonacular.com/recipes/{foodId}/information
API key is appended via query params.

Data fetched in useEffect using native fetch().

4. 📱 Responsive Layout
Built with Flexbox or CSS Grid via CSS Modules.

Two-panel layout:

Sidebar on the left (recipe list)

Main content on the right (details)

5. 🖼 Image & UI Enhancements
Ingredient images and recipe photos enhance UX.

Clean and modern UI styled using scoped CSS classes.

Web App Preview Image:
<img width="1902" height="842" alt="image" src="https://github.com/user-attachments/assets/ef22b479-375c-4d85-91fa-0b8b92a37f45" />

 How to Run Locally

# 1. Clone the repository
git clone https://github.com/your-username/your-repo.git

# 2. Navigate into the project directory
cd repo

# 3. Install the dependencies
npm install

# 4. Start the development server
npm run dev
# or
npm start

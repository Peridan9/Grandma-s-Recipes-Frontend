# 🍲 Grandma's Recipes - Frontend 🍴

This repository contains the **frontend** implementation for the "Grandma's Recipes" project, developed as part of the **Web Development Environments** course at Ben-Gurion University. The frontend was built using **Vue.js**, leveraging design libraries like **Bootstrap** for styling and responsiveness.

---

## ✨ Features

- **User Authentication:**
  - Registration and login forms with input validation.
  - Visual feedback for invalid input during registration.

- **Recipe Management:**
  - Display family, personal, and general recipes fetched from the backend and external APIs.
  - Add new recipes to family or personal collections.
  - View recipe details, including ingredients, steps, and nutritional information.

- **Search and Filter:**
  - Search for recipes by name or keyword.
  - Filter recipes by category or other attributes.

- **Interactive UI:**
  - Responsive design with dynamic components.
  - Customized styles for improved user experience.

---

## 🛠️ Technologies Used

- **Vue.js**: Core framework for building the frontend.
- **Bootstrap**: For styling and ready-to-use components.
- **Vue CLI**: Project scaffolding and configuration.

---

## 📂 File Structure

```
Grandma-s-Recipes-Frontend/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   │   ├── logo.png
│   │   └── styles.css
│   ├── components/
│   │   ├── Login.vue
│   │   ├── Register.vue
│   │   ├── RecipeList.vue
│   │   ├── RecipeDetails.vue
│   │   └── AddRecipe.vue
│   ├── router/
│   │   └── index.js
│   ├── store/
│   │   └── index.js
│   ├── views/
│   │   ├── Home.vue
│   │   ├── Recipes.vue
│   │   ├── FamilyRecipes.vue
│   │   ├── PersonalRecipes.vue
│   │   └── About.vue
│   ├── App.vue
│   └── main.js
├── .gitignore
├── README.md
├── package.json
└── package-lock.json
```

---

## 🖍️ Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Peridan9/Grandma-s-Recipes-Frontend.git
   cd Grandma-s-Recipes-Frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run serve
   ```

4. **Access the application:**
   ```
   http://localhost:8080
   ```

---

## 🔗 Backend Integration

The frontend interacts with the backend service (refer to the [Backend Repository](https://github.com/Peridan9/Grandma-s-Recipes-backend)) to:
- Fetch user-specific recipes (family and personal).
- Query general recipes from external APIs.
- Perform user authentication and authorization.

---

## 🌟 Design and Styling

- **Bootstrap and Bootstrap-Vue:** Used for layouts and responsive design.
- **Custom Components:** The project separates functionality into reusable Vue components.
- **Validation and Feedback:** Ensures smooth user experience with input validation and feedback mechanisms.

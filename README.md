# 🎬 MovieApp

A modern, responsive React movie application powered by Vite that allows users to search for popular movies, view detailed movie cards, and manage a personalized list of favorite movies using React Context.

---

## 🚀 Features

- **Movie Search & Discovery:** Search and discover trending movies dynamically via API integration.
- **Favorites Management:** Add or remove movies to/from a personal favorites list managed through React Context.
- **Modular Component Structure:** Separated components for navigation, movie cards, page views, and API logic.
- **Fast Build Tooling:** Lightning-fast HMR and building powered by Vite.

---

## 🛠️ Tech Stack

- **Framework:** React.js
- **Build Tool:** Vite
- **State Management:** React Context API (`MovieContext.jsx`)
- **Styling:** CSS3
- **API Integration:** Custom service module (`api.js`)

---

## 📁 Project Structure

```text
MovieApp/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── MovieCard.jsx       # Individual movie card component
│   │   └── NavBar.jsx          # Top navigation bar
│   ├── contexts/
│   │   └── MovieContext.jsx    # React Context state for favorites
│   ├── css/
│   │   ├── App.css
│   │   ├── Favorites.css
│   │   ├── Home.css
│   │   ├── index.css
│   │   ├── MovieCard.css
│   │   └── Navbar.css
│   ├── pages/
│   │   ├── Favorites.jsx       # Favorites page view
│   │   └── Home.jsx            # Main home/search page view
│   ├── services/
│   │   └── api.js              # Movie API request handlers
│   ├── App.jsx                 # Application layout & routing
│   └── main.jsx                # React root entry point
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

---

## ⚙️ Installation & Setup

Follow these steps to run the application locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/parthdhamejani/MovieApp.git](https://github.com/parthdhamejani/MovieApp.git)
   ```

2. **Navigate into the project directory:**
   ```bash
   cd MovieApp
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the Vite development server:**
   ```bash
   npm run dev
   ```

5. **Open in browser:**
   Open your browser and navigate to `http://localhost:5173` (or the local URL displayed in your terminal).

---

## 📜 Available Scripts

In the project directory, you can run:

- `npm run dev` — Starts the Vite development server.
- `npm run build` — Builds the application for production.
- `npm run lint` — Checks code against ESLint rules.
- `npm run preview` — Previews the production build locally.
```

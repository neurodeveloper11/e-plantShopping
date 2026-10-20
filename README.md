# Paradise Nursery - Online Houseplant Shopping Application (e-plantShopping)

Welcome to **Paradise Nursery** (`e-plantShopping`), an interactive, responsive e-commerce web application for plant enthusiasts, developed as the Final Project for the IBM Front-End Developer specialization.

## 🌿 Live Application Demo
- **Deployed URL (GitHub Pages):** [https://neurodeveloper11.github.io/e-plantShopping/](https://neurodeveloper11.github.io/e-plantShopping/)
- **Repository:** [https://github.com/neurodeveloper11/e-plantShopping](https://github.com/neurodeveloper11/e-plantShopping)

---

## 📌 Project Overview
Paradise Nursery brings nature closer to homes and offices by offering a wide variety of indoor houseplants. The application provides an engaging user experience with dynamic state management powered by React and Redux Toolkit.

### 🌟 Key Features

1. **Landing Page:**
   - Visual greenhouse background image with immersive overlay styling.
   - Company branding: *"Welcome to Paradise Nursery - Where Green Meets Serenity"*.
   - Informative **About Us** section describing company history, values, and environmental mission.
   - Interactive **"Get Started"** button transitioning smoothly into the product catalog.

2. **Product Listing Page:**
   - **30+ Unique Houseplants** organized across **5 distinct categories**:
     - *Air Purifying Plants* (Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera)
     - *Aromatic Fragrant Plants* (Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth)
     - *Insect Repellent Plants* (Oregano, Marigold, Geraniums, Basil, Citronella, Catnip)
     - *Medicinal Plants* (Aloe Vera Medicinal, Echinacea, Peppermint, Lemon Balm Herbal, Chamomile, Calendula)
     - *Low Maintenance Plants* (ZZ Plant, Pothos, Snake Plant Hardy, Cast Iron Plant, Succulents, Aglaonema)
   - Every product card includes high-resolution thumbnail images, botanical names, plant benefits descriptions, and unit prices.
   - **"Add to Cart"** functionality that adds the item to the global store, dynamically disables the button, changes its appearance to grey, and displays *"Added to Cart"*.

3. **Persistent Navigation & Cart Badge:**
   - Universal navbar present on both the catalog and shopping cart views.
   - Live cart icon with a real-time badge indicator reflecting the exact total quantity of plants in the basket.
   - Quick navigation links between **Home**, **Plants**, and **Cart**.

4. **Interactive Shopping Cart:**
   - Summarizes total plants in the basket and the overall cart dollar amount (`$`).
   - Detailed breakdown for each selected plant: thumbnail image, name, unit cost, quantity controls (`+` and `-`), subtotal cost, and a **Delete** action.
   - Decreasing an item at quantity 1 gracefully removes it from the basket.
   - **Continue Shopping** button returning users seamlessly to the catalog.
   - **Checkout** button providing immediate visual confirmation ("Coming Soon / Functionality to be added for future reference").

---

## 🛠️ Technology Stack
- **Library/Framework:** React 18 (Functional Components, Hooks: `useState`, `useEffect`)
- **State Management:** Redux Toolkit (`createSlice`, `configureStore`, `useDispatch`, `useSelector`)
- **Build Tool:** Vite 5
- **Styling:** CSS3 (Flexbox, Grid, Responsive Media Queries)
- **Deployment:** GitHub Pages (`gh-pages`)

---

## 🚀 Local Development Setup

To run this application locally on your machine:

```bash
# Clone the repository
git clone https://github.com/neurodeveloper11/e-plantShopping.git

# Navigate into the project folder
cd e-plantShopping

# Install dependencies
npm install

# Start local development server
npm run dev
```

---

## 👤 Author
- **Developer:** Fabio Torres ([@neurodeveloper11](https://github.com/neurodeveloper11))
- **Program:** IBM Professional Frontend / Full Stack Development Certification
- **License:** Apache License 2.0

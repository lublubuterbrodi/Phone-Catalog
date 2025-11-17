# Phone Catalog

Phone Catalog is a single-page web application where users can browse different smartphone models, view detailed specs, compare prices, and manage favorites and cart items.
The project was developed as a React + TypeScript learning task with a focus on clean architecture, reusable components, and responsive UI.

---

## 🚀 Live Demo

You can view the deployed version here:

🔗 https://lublubuterbrodi.github.io/Phone-Catalog/

---

## 🎨 Design Reference

The layout is based on the course design mockup with several custom improvements and adjustments.
(If needed, a Figma link can be added.)

---

## 🛠️ Technologies Used

### Core

- **React** — main UI library
- **TypeScript** — static typing and error prevention
- **SCSS** — modular styling

### Routing & State

- **React Router** — multi-page navigation inside the SPA
- **React Context** — global state for cart and favorites
- **LocalStorage** — persistence across page reloads

### Development

- **Vite** — fast development server and build tool
- **ESLint** — code quality and formatting
- **GitHub Pages** — deployment

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/lublubuterbrodi/Phone-Catalog.git
cd Phone-Catalog

### 2. Install dependencies
npm install
# or
yarn install

### 3. Run the project locally
npm run dev
# or
yarn dev


The app will be available at a URL similar to:

http://localhost:5173
```

## ✨ Features

- **Responsive Layout**
  Works smoothly on mobile, tablet, and desktop screens.

- **Phone Catalog**
  View a list of phone models with images, prices, and short descriptions.

- **Product Details Page**
  Displays full specifications, large product images, and additional info.

- **Favorites System**
  Add/remove items from favorites. Data is saved in LocalStorage.

- **Shopping Cart**
  Add items, update quantities, and see the total cost dynamically.

- **Sorting Options**
  Sort items by price, alphabetical order, or release order.

- **Filtering**
  Narrow down the catalog using various parameters (e.g., brand, price).

- **Search Functionality**
  Instantly find models by typing part of the name.

- **Pagination / Items per Page**
  Convenient navigation through larger lists.

- **Breadcrumb Navigation**
  Helps users understand their location within the app.

- **Sticky Header**
  Keeps the navigation always accessible when scrolling.

- **Scroll to Top Button**
  Quick return to the top of the catalog page.

- **Skeleton Loaders**
  Smooth loading experience when fetching data.

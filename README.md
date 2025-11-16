# Phone Catalog – Online Mobile Store

This project is a modern single-page application for browsing a catalog of mobile phones.
Users can explore a list of smartphones, view detailed product information, compare specifications and prices, add items to favorites or a shopping cart, and manage their selections with a clean and responsive interface.

---

## Live Preview

Add a link to the deployed version of your project.

**Live Demo**

Experience the live website: [Phone Catalog Demo](https://lublubuterbrodi.github.io/Phone-Catalog/)

> ⚠️ Make sure the link is **publicly accessible**. Test it in incognito mode to verify functionality.

---

## Design Reference (If Applicable)

If the project is based on a specific design, include a link to the Figma file or design reference here.

Example:

- Figma Design: `https://www.figma.com/file/your-design-link`

---

## Technologies Used 🧰

List of the main technologies and frameworks used in the project.

### Core

- **React (v18.x)** – UI library
- **TypeScript (v5.x)** – Type safety
- **SCSS (v1.x)** – Styling and component-based styles

### State Management

- **React Context / Custom Hooks** – Application state (cart, favorites, filters)
  <!-- If you use Redux, replace the line above with:
  - **Redux Toolkit (vX.X.X)** – Application state management
  -->

### UI/UX

- **React Router (v6.x)** – Client-side routing and navigation
- **React Loading Skeleton / Custom Loader** – Loading states
- **LocalStorage API** – Persistence for favorites and cart

### Development & Deployment

- **Vite (v4.x)** – Build tool and development server
- **ESLint (v8.x)** – Code quality and linting
- **GitHub Pages** – Hosting and deployment

---

## Getting Started

Include these instructions on how to set up the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Phone-Catalog.git
cd Phone-Catalog
```

Replace lublubuterbrodi with your GitHub username if you fork this project.

### 2. Install dependencies

npm install

# or

yarn install

### 3. Run the project locally

npm run dev

# or

yarn dev

Open the URL shown in the terminal (usually http://localhost:5173) in your browser.

## Features (optional)

Highlight key features or functionalities that make your project stand out.

### Features

- **Responsive Design**
  Optimized for different screen sizes and devices, with breakpoints for popular widths (mobile, tablet, desktop).

- **Phone Catalog**
  Browse a grid/list of phones with basic information such as name, image, price, and short description.

- **Product Details Page**
  View detailed information for each phone: full description, specifications, price, and high-resolution images.

- **Favorites**
  Add and remove phones from a favorites list. Favorite items are persisted in localStorage, so they remain after page reloads.

- **Shopping Cart**
  Add phones to a cart, update quantities, remove items, and see a summary of the total price and number of items.

- **Sorting**
  Sort products by price (low–high / high–low), name (alphabetically), and possibly by new/old models.

- **Filtering**
  Filter phones by brand, category, or other parameters (e.g., price range, in stock).

- **Search**
  Quickly find phones by name or part of the model name using a search input.

- **Pagination / “Items per page”**
  Navigate through large lists of phones with pagination or configurable items per page.

- **Navigation & Breadcrumbs**
  Client-side routing between pages (home, catalog, favorites, cart, details). Breadcrumbs help users understand their current location in the app.

- **Sticky Header**
  Keeps the main navigation visible while scrolling.

- **Scroll to Top Button**
  Allows users to quickly return to the top of the page after scrolling through long lists.

- **Loaders & Skeletons**
  Visual placeholders displayed while data is being fetched for a smoother user experience.

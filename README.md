# 👟 Sneakers Store — React & Redux Toolkit

A modern, high-performance e-commerce frontend platform built strictly on top of the **Feature-Sliced Design (FSD)** architectural methodology.

---

### 🚀 Live Demo
[View Live Demo on GitHub Pages](https://nfluvv.github.io/lace-it)

---

### ✨ Key Features
*   **Dynamic Product Catalog:** Optimized data fetching and rendering of product grids.
*   **Wishlist Management:** LocalStorage-backed persistence for saved products with optimistic UI updates.
*   **Shopping Cart:** Real-time state updates, item mutation handling, and automated price calculation.
*   **Instant Search & Filtering:** Dynamic, real-time client-side search query processing.
*   **Fully Responsive UI:** Production-ready adaptive layout optimized for all mobile and desktop devices.

---

### 🛠 Tech Stack
*   **UI Framework:** React
*   **State Management:** Redux Toolkit
*   **Styling:** SCSS Modules
*   **Architecture:** Feature-Sliced Design (FSD)
*   **Routing:** React Router Dom v6

---

### 🏗 Architecture & Codebase Structure

The project strictly adheres to the architectural guidelines of FSD:
*   `app/` — Application entry point, global styles, and core providers (Redux Store, Router).
*   `pages/` — Composition layer assembling standalone app screens (Home, Favorites, Cart).
*   `widgets/` — High-level structural components (Header, ProductList) combining features and entities.
*   `features/` — Business logic handling user interactions (AddToCart, ToggleFavorite).
*   `entities/` — Domain business entities and shared layout items (ProductCard, CartItem).
*   `shared/` — Reusable abstract modules: generic UI-kit components, API clients, and helper utilities.

---

### 💻 Installation & Quick Start

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/mattuzik/lace-it
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm start
    ```

---

### 📦 Deployment
Building and deploying the static build configuration for production hosting (GitHub Pages):
```bash
npm run build
npm run deploy
```

---

### 📝 License
This project is open-source and available under the MIT License.

## [DEMO LINK](https://martachobaniuk.github.io/nice_gadgets_app/)

# Nice Gadgets App

The Nice Gadgets App is a product catalog platform built with React and TypeScript. It allows users to browse different categories of phones, tablets, and accessories, apply filters, view product details, and manage their shopping cart and favorites.

## Technologies Used

- **React**: Frontend framework for building the UI.
- **TypeScript**: Ensures type safety and better maintainability..
- **SCSS**: Provides styling with modular and reusable styles.
- **CSS Modules**: For scoping styles and avoiding conflicts.
- **Classnames**: Helps manage dynamic class names.
- **React Router**: Handles navigation between pages.
- **React Context**: Used for managing cart, favorites and theme.
- **LocalStorage**: For storing cart, favorites and theme data persistently.

## Folder Structure

- `index.html`: Main HTML file
- `/public/api`: Contains the product data.
- `/public/img`: Contains the product images.
- `/src/components`: Contains React components like Header, ProductList, Footer, ProductCard, etc.
- `/src/pages`: Contains individual page modules like HomePage, CartPage, and others.
- `/src/types`: Defines TypeScript types and interfaces for products and other components.
- `/src/hooks`: Custom React hooks for reusable logic.
- `/src/utils`: Contains utility functions for sorting, fetching products, etc.
- `/src/api`: Handles API interactions to fetch product data.

## Features

- **Product Catalog**: Users can browse products by category, view details, and sort by different criteria (e.g., newest, cheapest, alphabetically).
- **Product Pages**: Dedicated pages for phones, tablets, and accessories, with relevant product information and features.
- **Product Sorting and Pagination**: Ability to sort products and paginate through the catalog.
- **Cart Management**: Add products to the shopping cart, update quantities, and remove items.
- **Favorites**: Add/remove products from favorites and persist them across sessions.
- **Responsive Design**: Adaptive layout for various screen sizes.
- **Error Handling**: Displays error messages if API calls fail or if no products are found.

## Commands

| Name    | Command         |
| ------- | --------------- |
| Install | `npm install`   |
| Start   | `npm run start` |
| Build   | `npm run build` |

## App Logic Overview

- Users can browse and filter products by category (Phones, Tablets, Accessories).
- Products are displayed in a paginated list with sorting options (Newest, Alphabetically, Cheapest).
- Users can add products to their cart, view cart items, and modify quantities.
- Products can be added to or removed from the favorites list.
- Cart and favorites data are stored in localStorage, ensuring persistence across sessions.
- A loader is displayed when data is being fetched, and error messages are shown in case of failure.
- The shopping cart has a checkout button that opens a modal for confirming cart clearing.
- Each product page provides detailed information, and users can select colors and capacities.

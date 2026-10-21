# ePlantShopping 🌱

## 🛠️ Technologies
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white)

A plant shopping application built with React, Redux Toolkit, and Vite. The project simulates an online plant store, allowing users to browse products and manage their shopping cart.

## Features

- Browse available plants.
- Add and remove products from the shopping cart.
- Increase or decrease item quantities.
- View cart items and their respective prices.
- Manage cart state using Redux Toolkit.
- Responsive and component-based interface.

## Technologies

- **React** — Building the user interface with reusable components.
- **Redux Toolkit** — Centralized state management for the shopping cart.
- **JavaScript** — Application logic.
- **CSS** — Styling and layout.
- **Vite** — Development server and build tool.
- **GitHub Pages** — Deployment.

## Project Structure

```text
src/
├── app/
│   └── store.js
├── components/
│   ├── AboutUs.jsx
│   ├── AboutUs.css
│   ├── CartItem.jsx
│   └── CartItem.css
├── features/
│   └── cart/
│       └── CartSlice.jsx
├── pages/
│   ├── ProductList.jsx
│   └── ProductList.css
├── App.jsx
└── main.jsx
```

## Getting Started

### Prerequisites

- Node.js
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd e-plantShopping
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

## Build

To create a production build:

```bash
npm run build
```

## Deployment

The application is deployed using GitHub Pages.

## Learning Objectives

This project was developed as part of my full-stack development learning journey, with a focus on:

- Structuring a React application.
- Creating reusable components.
- Managing shared state with Redux Toolkit.
- Implementing Redux actions and reducers.
- Organizing application code by responsibility.

## Author

Lucas Sperafico

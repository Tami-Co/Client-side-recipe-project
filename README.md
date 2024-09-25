# Recipe Sharing Website - Client (Frontend)

This repository contains the frontend for the Recipe Sharing Website, built with Angular. The frontend connects to the backend API to manage users, recipes, and categories, providing a responsive and user-friendly interface.

## Features

- Users can create, update, and delete recipes.
- Recipes are categorized for easier browsing.
- Users can search for recipes by name or category.
- Responsive design for both mobile and desktop.
- User authentication and authorization via JWT.
- Recipe sharing options: public or private.

## Technologies Used

- **Angular**: JavaScript framework for building client-side applications.
- **Angular Material**: UI component library for a modern, responsive layout.
- **RxJS**: Library for handling reactive programming with observables.
- **Reactive Forms**: Used for handling dynamic forms and implementing form validation.
- **HTTP Client**: For making API calls to the backend.
- **JWT (JSON Web Token)**: Used for user authentication and session management.

## Installation

### Prerequisites

- Node.js (v14+)
- npm (Node Package Manager)
- Angular CLI (v12+)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tami-Co/Client-side-recipe-project/.git
2. **Navigate to the client folder and install dependencies**:
   cd client-side
   npm install
3. **Run the frontend (client)**:
    ng serve

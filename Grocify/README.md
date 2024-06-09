# Grocery Delivery Service Landing Page

Welcome to the Grocery Delivery Service Landing Page repository! This project showcases a simple, beginner-friendly landing page for a grocery delivery service, built using Tailwind CSS.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project is a static landing page designed for a grocery delivery service. It is intended to be an easy-to-understand and implement example for beginners who are learning how to create responsive and visually appealing web pages using Tailwind CSS.

## Features

- Responsive design that works on all devices
- Clean and modern user interface
- Utilizes Tailwind CSS for styling
- Easy to customize and extend

## Technologies Used

- HTML
- Tailwind CSS

## Getting Started

To get a local copy of this project up and running, follow these simple steps.

### Prerequisites

You need to have the following software installed on your local machine:

- Git
- Node.js (for Tailwind CSS CLI)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/grocery-delivery-landing-page.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd grocery-delivery-landing-page
   ```

3. **Install Tailwind CSS via npm**

   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

4. **Configure Tailwind CSS**

   Add the following content to your `tailwind.config.js` file:

   ```javascript
   module.exports = {
     purge: ['./src/**/*.{html,js}'],
     darkMode: false, // or 'media' or 'class'
     theme: {
       extend: {},
     },
     variants: {
       extend: {},
     },
     plugins: [],
   }
   ```

5. **Create a Tailwind CSS file**

   Create a `src/styles/tailwind.css` file and add the following:

   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

6. **Build Tailwind CSS**

   ```bash
   npx tailwindcss build src/styles/tailwind.css -o public/styles.css
   ```

7. **Open the `index.html` file in your browser**

   Simply open the `index.html` file located in the root directory of the project in your preferred web browser.

## Usage

Feel free to use this project as a template for your own grocery delivery service landing page or for any other similar project. You can customize the content and styles as needed to fit your requirements.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue. Let's make this project better together.

Thank you for checking out this project! Happy coding!

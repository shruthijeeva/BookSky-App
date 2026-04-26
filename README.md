# Booksky: A Dynamic Book Management Web App

Booksky is a sleek, responsive web application for book lovers to organize their personal reading lists. Built with core front‑end technologies, this project demonstrates DOM manipulation, event handling, and modern UI/UX design.

## Project Overview

The app allows users to digitally catalog their books with a clean, card‑based interface. Users can add new titles with descriptions and remove them as their collection changes, all without refreshing the page. The project emphasizes a seamless user experience using modal popups and dynamic content rendering.

## Key Features

- Dynamic Book Cataloging: Users can add books in real time using a custom modal form.  
- CRUD Operations (Front‑end): Implementation of Create and Delete functionality through JavaScript DOM methods.  
- Responsive UI/UX: Designed with a mobile‑first mindset using CSS Flexbox and Inline‑Block layouts.  
- Interactive Elements: Floating action button to add books, and a popup overlay system to focus attention on data entry.  
- Modern Aesthetics: Uses the Poppins font family and a high‑contrast color palette (Coral and Dark Mode) for better readability.

## Tech Stack

- HTML5: Structured semantic markup for the library interface  
- CSS3: Custom styling with absolute positioning, z‑index management for modals, and responsive container layouts  
- JavaScript (ES6):
  - querySelector and getElementById for element selection  
  - addEventListener for handling clicks and form submissions  
  - createElement and template literals for dynamic HTML generation

## File Structure

- booksky.html – Core structure of the application, including navigation, book container, and hidden modal elements.  
- bookskystyle.css – Stylesheet for the dark‑themed book cards and overlay effects.  
- bookskyscript.js – Script that handles opening and closing the “Add Book” popup and appends new book cards to the dashboard.

## How It Works

1. Adding a Book: Click the floating “+” button to open the popup overlay.  
2. Form Submission: Enter the Title, Author, and a short Description.  
3. Real‑time Update: JavaScript captures the input and instantly appends a new styled card to the library container.  
4. Management: Each book card has a “Delete” option to remove the entry during the current session.

This project serves as a showcase of fundamental front‑end engineering skills, demonstrating how JavaScript can turn a static HTML page into a functional, interactive web application.

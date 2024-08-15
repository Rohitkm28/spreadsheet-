
# Spreadsheet  Frontend Application

## Introduction
This project is a frontend application built with **Next.js** and **Tailwind CSS** that mimics the functionality of a spreadsheet. It features grid rendering, cell editing, basic cell formatting, and additional advanced functionalities like search, filter, undo/redo, and data validation. This project is designed to assess skills in frontend development, state management, and UI/UX design, focusing on performance, responsiveness, and code quality.

## Features

### Core Functionality
- **Grid Rendering**: Efficiently render a grid of 1000 blank cells with smooth scrolling and optimized performance.
- **Cell Editing**: Each cell is editable, allowing users to dynamically input and update cell content.
- **Data Storage**: All cell data is stored in memory using `zustand` for state management, ensuring persistence during interaction.
- **Styling**: Cells are styled to visually distinguish them, using grid lines, padding, and custom font styles.


## Core Functionality

### 1. **Grid Rendering**
The grid contains 1000 cells and is optimized for performance to ensure smooth scrolling and interaction. Tailwind CSS is used for styling, ensuring the cells are responsive and styled with grid lines, padding, and font.

### 2. **Cell Editing**
Each cell is individually editable, allowing the user to input and store data in memory via `zustand` state management. Changes made in any cell are dynamically reflected across the grid.

### 3. **Data Storage**
Data entered into each cell is managed with `zustand` to maintain state in memory, ensuring data persists while interacting with the grid.

### 4. **Cell Styling**
Grid cells are visually styled with clear grid lines and interactive elements, making the application closely resemble a traditional spreadsheet.



## Dependencies
- **Next.js**: React framework for building the frontend.
- **Zustand**: For lightweight state management.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **React Icons**: For providing a clean, modern user interface.


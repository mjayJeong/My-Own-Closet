# My Own Closet 👕

JAVA Programming Lab - Final Project

---

## Project Overview

**My Own Closet** is a personal project designed to help users easily manage their wardrobe and make outfit decisions. The program enables users to register, view, and combine their clothing items into coordinated outfits, providing a simple and user-friendly interface.

### Purpose
- Simplify the process of selecting and matching clothes.
- Allow users to register all their clothes, view them by category, and simulate outfit combinations.

---

## Features

### 1. User Registration and Login
- Users can register and log in to access their wardrobe.
- **File I/O** is used to store user credentials and verify them during login.

### 2. Clothes Registration
- Add clothing items by selecting:
  - **Category**: Top, Bottom, Outer, Shoes.
  - **Type**: Specific type of clothing (e.g., Hoodie, Shirt, Pants).
  - **Color**: Colors predefined for each category.
- If any required field is missing, an error message is displayed.
- Clothing items are stored in an **ArrayList** for efficient management.

### 3. Closet View
- View all registered clothes or filter by category.
- The system displays:
  - Thumbnails of each clothing item.
  - Count of items in each category (managed using **Threads**).
- Users can delete unwanted items using a dedicated dialog.

### 4. Outfit Combination
- Combine clothes into outfits:
  - Select items from each category (Top, Bottom, Outer, Shoes).
  - Combine them to see a preview of the outfit.
- **GridLayout** is used to position the selected clothing images correctly.

---

## Technical Implementation

### 1. Object-Oriented Principles
- **Class and Inheritance**: Used for GUI components and functional modules.
- **Polymorphism**: Implemented via `ActionListener` for handling button actions.

### 2. Graphical User Interface
- Built using **Swing** for a visually intuitive interface.

### 3. File I/O
- Used for:
  - Storing and verifying user credentials.
  - Retrieving and displaying clothing images.

### 4. Generic Collections
- **ArrayList**: Stores clothing items.
- **Map**: Links clothing items to their respective images.

### 5. Threads
- Counts clothing items in each category dynamically while viewing the closet.

---

## Notes on Clothing Images
- Free copyright images were sourced from [Freepik](https://www.freepik.com/).
- Images were recolored using **Naver Webtoon AI Painter** for variety.

---

## Limitations and Future Improvements

### Current Limitations
- Recommendation functionality for outfits was not implemented due to the complexity of creating an effective algorithm.
- Limited time prevented the addition of more clothing items (e.g., women's clothing).

### Future Improvements
- Implement a recommendation system for outfits using tags or advanced algorithms.
- Add a feature to upload custom clothing images directly.
- Expand the database to include more diverse clothing options.

# Responsive Product Card

## Overview
This project showcases a responsive product card built using **Tailwind CSS**. The card features a classic 35mm vintage film camera, complete with an image, title, description, and a "Buy Now" button. The card is designed to be responsive, ensuring it looks great on devices of all sizes—from mobile phones to large desktop monitors.

## Features
- **Responsive Design**: Utilizes Tailwind CSS's responsive utilities to adapt the card layout based on screen size.
- **Clean, Structured Code**: The code follows best practices for readability and maintainability.
- **Tailwind CSS Utility Classes**: Demonstrates the use of Tailwind's utility-first approach for fast, flexible styling.

## Technology Used
- **HTML**: For the basic structure and content.
- **Tailwind CSS**: For styling and responsive design.

## Code Explanation
- **Responsive Width**:
  - `max-w-sm`, `md:max-w-md`, and `lg:max-w-lg` adjust the card's width based on screen size.
- **Responsive Image Height**:
  - `h-64`, `md:h-80`, and `lg:h-96` modify the image height to keep it proportional.
- **Responsive Text Sizes**:
  - Title (`text-lg`, `md:text-xl`, `lg:text-2xl`) and description (`text-sm`, `md:text-base`, `lg:text-lg`) scale up for better readability.
- **Hover Effects**:
  - The "Buy Now" button includes hover styling (`hover:bg-blue-600`) for an interactive experience.

## Usage
1. Copy the code and save it as `product-card.html`.
2. Open the HTML file in your browser.
3. Resize the browser window to see how the card adjusts at different breakpoints (small, medium, and large screens).

## Preview
![Product Card Preview](screenshot.png)

## Installation
Ensure you have an internet connection to load the Tailwind CSS CDN in the `<script>` tag:
```html
<script src="https://cdn.tailwindcss.com"></script>

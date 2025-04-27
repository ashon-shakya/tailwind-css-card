# Tailwind CSS Post Card Component

## Description

This project contains an HTML file (`index.html` or similar) that displays a responsive post card component styled entirely using **Tailwind CSS** (via the CDN). The design is based on a provided image, featuring an image header, content area (time ago, title, description), and a colored footer displaying statistics (read time, views, comments).

This example demonstrates how to structure and style a common UI element using Tailwind's utility-first approach.

## Features

- Responsive card layout.
- Image header using `object-cover`.
- Clear separation of content and statistics.
- Styled footer with distinct background color (easily customizable for different card variations).
- Uses Tailwind CSS utility classes for all styling.
- Includes Google Fonts (`Inter`) for typography.

## Technology Used

- HTML5
- Tailwind CSS v3 (via CDN)
- Google Fonts (Inter)

## How to Use

1.  **Save the Code:** Ensure you have the HTML code saved in a file (e.g., `card.html`).
2.  **Open in Browser:** Simply open the `card.html` file in your web browser.
3.  **Internet Connection:** An internet connection is required for the Tailwind CSS CDN and Google Fonts to load correctly.

## Customization

- **Content:** Modify the text content directly within the HTML tags (e.g., change "Post One", the description text, and the stats).
- **Image:** Replace the `src` attribute of the `<img>` tag with your desired image URL. The placeholder uses `placehold.co`.
- **Footer Color:** Change the background color class in the footer `div`. For example, change `bg-pink-500` to `bg-orange-500` or `bg-green-500` to match the other cards in the original design.
- **Layout:** Adjust `max-w-xs` on the main card container to change the card's maximum width.

## Tailwind Class Explanations

For a detailed breakdown of the specific Tailwind CSS utility classes used in this component and what they do, please refer to the **"Tailwind CSS Class Explanations for Card"** document (ID: `tailwind_card_classes`).

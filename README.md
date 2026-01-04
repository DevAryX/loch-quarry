# Loch Quarry (Lochquarry Outdoor Centre) Website

A simple multi-page website for **Lochquarry Outdoor Centre**, built using **HTML + CSS** (with a small JavaScript review slider on the Home page). The site includes a consistent sticky navigation header across pages and separate sections for different activity types.

## Pages

- **Home** (`Home.html`)  
  Landing/hero image, quick links to activity pages, rotating reviews, and a basic contact form.
- **About Us** (`About.html`)  
  Centre overview + staff section and a customer quote.
- **Land Activities** (`Land.html`)  
  Activity cards (e.g., hillwalking, archery, orienteering, axe throwing) with group sizes and age tags.
- **Water Activities** (`Water.html`)  
  Activity cards (kayaking, canoeing, powerboating) with group sizes and age tags.
- **Rope Adventures** (`Rope.html`)  
  Rope-based activities (climbing, abseiling, pole climb) with group sizes and age tags.

## Features

- Sticky header navigation across all pages
- Simple, consistent colour theme and typography
- Activity “card” layout with hover effects
- Reviews section on the Home page that rotates automatically
- Basic contact form layout (front-end only)

## Tech Used

- HTML5
- CSS (embedded in each page)
- JavaScript (Home page review rotator)

## How to Run Locally

### Option 1: Quick open
1. Download/clone this repo
2. Open `Home.html` in your browser

### Option 2: Run with a local server (recommended)
Using VS Code:
1. Install the **Live Server** extension
2. Right-click `Home.html` → **Open with Live Server**

Using Python:
```bash
# from the repo folder
python -m http.server 8000
```
Then open: http://localhost:8000/Home.html

Assets / Images

The pages reference image files such as:

logo.png

Landscape.jpg

Group.jpeg

Activity images like Hills.jpeg, Archery.jpg, Kayak.jpg, etc.

Make sure these are stored in the same folder as the HTML files (or update the paths if you move them).

Notes / Improvements To Add Later

Make the contact form functional (e.g., Formspree / backend endpoint)

Move repeated CSS into a single styles.css file

Add a shared footer link set and consistent external links

Improve accessibility (alt text consistency, keyboard focus styles)

Add a mobile nav menu for smaller screens

### Author

DevAryX

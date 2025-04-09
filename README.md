# Daily Scoop
**A News Reader Web App**

**Slogan:** Your Daily Dose of Fresh Headlines.

---

## Core Functionalities

### Search Bar
- Create an input field and a button.
- Use the `fetch` API to retrieve news articles based on user input.

### Dynamic Content Display
- Render articles dynamically as cards (including title, description, and image) by manipulating the DOM using `document.createElement` and `appendChild`.

### Sorting Articles
- Allow sorting articles by categories (e.g., Technology, Sports) using drop-downs or buttons.

### Responsive Design
- Use media queries for layout adjustments.
- Apply conditional styling with JavaScript (`element.style`).

---

## User Experience Enhancements

### Bookmark Feature
- Store saved articles in `localStorage` to keep them available even after page reloads.

### Real-Time Updates
- Auto-refresh articles every few seconds using `setInterval` to periodically fetch new data.

### Hover Effects
- Add visual effects like a card shadow when hovered using `element.classList.add()` and `element.classList.remove()` for styling classes.

### Dark Mode
- Toggle a dark/light theme using a button to dynamically change background and text colors.

---

## Interactive Elements

### Pagination
- Show articles in batches (e.g., 10 per page) with **Next** and **Previous** buttons.
- Use JavaScript to handle page navigation.

### Search Result Highlights
- Highlight keywords in the search results using `innerHTML` with string manipulations.

---

## Accessibility Features

### Adjustable Font Size
- Create buttons to increase or decrease font size dynamically using CSS variables and JavaScript.

### Offline Mode
- Cache fetched articles using `localStorage`, allowing users to access previously loaded content even when offline.

---

## Bonus Fun Ideas

### Click-to-Expand Articles
- Show a detailed view of an article when a user clicks on it, opening the content in a modal.

### Share Button
- Add a shareable link for articles using the `navigator.share` API (if supported) or by copying the URL directly to the clipboard.

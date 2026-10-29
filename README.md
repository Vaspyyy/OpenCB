# mise. | A little cookbook

A small, responsive personal recipe app built around the Material 3 design language: soft surfaces, expressive type, rounded components, thoughtful motion, and clear visual hierarchy.

## Recipes included

- **Kartoffelpuffer tasting menu**: savory garlic-yogurt and Gouda-crisp pancakes, plus sweet cinnamon-apple pancakes.
- **Spicy peanut-butter chicken ramen**: pantry-friendly noodles with optional chicken and jammy eggs.
- **Brown-butter Arme Ritter**: custardy French toast with cinnamon apples.
- **Crispy rösti with eggs and garlic yogurt**: a crisp potato cake with slow onions.

## Features

- Search by recipe, ingredient, or description
- Filter by savoury, sweet, comfort food, or favourites
- Save favourites locally in the browser
- Scale ingredient quantities by serving count
- Check ingredients off as you prep
- Step-by-step cooking mode
- Light and dark themes
- Responsive mobile layout and reduced-motion support
- Installable PWA shell with a small offline cache

## Run locally

No build step or package manager is needed. Open `index.html` in a browser, or serve the folder with any static file server:

```sh
python -m http.server 8000
``

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, select `main` and the `/ (root)` folder, and save. The app is a static site, so no build command is needed.

## Notes

Saved recipes and theme preference stay in the current browser via local storage. The UI uses the Material Symbols font and web fonts when online; the core app works without them. Recipe costs are broad ingredient-use estimates, not live supermarket prices.

# Module 5 Solution - HTML, CSS & JavaScript for Web Developers ([https://www.coursera.org/learn/html-css-javascript-for-web-developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers))

**Functionality:**

- Clicking on the "Specials" tile redirects the user to a random single category menu page displaying menu items for a specific category (e.g., Lunch, Dinner, Sushi).

**Solution Approach:**

1. **HTML Structure:**
   - The `home.html` file likely contains the "Specials" tile as a link element with an `href` attribute. 
   - Instead of modifying this file directly, we can use JavaScript to dynamically change the `href` attribute before the user clicks on the tile.

2. **JavaScript Implementation:**
   - The `script.js` file would be responsible for the following:
     - Fetch an array of category URLs or category identifiers from the server (or use a predefined list if server-side interaction isn't implemented).
     - Select a random category URL/identifier from the array.
     - Use JavaScript DOM manipulation techniques to access the "Specials" tile element (e.g., by its ID or class name).
     - Update the `href` attribute of the "Specials" tile element with the randomly selected category URL/identifier.

## Practical III

### Q1: You change the footer colour in styles.css. How many pages update? What if the same colour was only set with an inline style on index.html?

**Answer:** 
- Changing footer colour in `styles.css` updates **all 5 pages**.
- If the colour was only set with an inline style on `index.html`, **only index.html** would update.

---

### Q2: Which is more specific: h1 or #welcome? If both set color, which wins? Write a one-line proof from your page.

**Answer:** 
- `#welcome` is more specific than `h1`.
- `#welcome` wins because ID selectors have higher specificity than element selectors.

---

### Q3: Convert #0369a1 into an approximate rgb(...) value. Why do designers often prefer hex in stylesheets?

**Answer:**
- #0369a1 = rgb(3, 105, 161)
- Designers prefer hex because it is shorter, faster to type, industry standard, easy to copy/paste, and saves file size.

---

### Q4: Set a nav link to display: none, then to visibility: hidden. What is the difference in the layout?

**Answer:**
- `display: none;` removes the element and its space. Other elements shift to fill the gap.
- `visibility: hidden;` hides the element but keeps its space. A gap remains.

---

### Q5: In your wireframe, how many event cards appear side-by-side at phone width? At desktop width?

**Answer:**
- **Phone:** 1 card (stacked vertically)
- **Desktop:** 3 cards (in a row)

---

### Q6: Why must styles.css be linked AFTER the Bootstrap CSS file? What happens if you reverse the order and both set h1 colour?

**Answer:**
- `styles.css` must be linked AFTER Bootstrap so the custom styles override Bootstrap.
- If reversed, Bootstrap will override the custom styles.
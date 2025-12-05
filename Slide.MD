## **Slide Deck: 1-Day HTML Crash Course (Updated)**

---

### **Slide 1: Title Slide**

* **Title:** HTML Crash Course – 1 Day
* **Subtitle:** Build Your First Webpage from Scratch
* **Your Name / Date**
* Optional: Add an HTML or coding icon

---

### **Slide 2: What is HTML?**

* Stands for **HyperText Markup Language**
* Defines the **structure of webpages**
* Works with:
  * **CSS** → styles
  * **JavaScript** → behavior
* Tip: HTML is the “skeleton” of your webpage

---

### **Slide 3: Setting Up Your Workspace**

* Install a code editor: **VS Code, Sublime, Atom**
* Create a new file: `index.html`
* Basic structure:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Page</title>
  </head>
  <body>
  </body>
</html>
````

* Tip: Include `lang` and `meta viewport` for accessibility and responsiveness

---

### **Slide 4: Text & Headings**

* Headings: `<h1>` to `<h6>` (largest to smallest)
* Paragraphs: `<p>`
* Formatting:

  * `<strong>` → bold
  * `<em>` → italic
  * `<mark>` → highlight
* Activity Prompt: Add a heading and paragraph in your HTML file

---

### **Slide 5: Lists & Links**

* Lists:

  * `<ul>` → unordered
  * `<ol>` → ordered
  * `<li>` → list item
* Links: `<a href="URL">Link Text</a>`

  * Internal vs. external links
* Tip: Use meaningful link text for accessibility

---

### **Slide 6: Images & Multimedia**

* Images: `<img src="image.jpg" alt="Description">`
* Audio: `<audio src="audio.mp3" controls>`
* Video: `<video src="video.mp4" controls>`
* Tip: Optimize files for web and always provide fallback content

---

### **Slide 7: Tables**

* Structure:

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```

* Tips:

  * Use tables only for tabular data
  * Use `scope` attribute for headers to improve accessibility

---

### **Slide 8: Forms**

* `<form>` with inputs:

  * Text: `<input type="text">`
  * Email: `<input type="email">`
  * Submit: `<input type="submit">`
* `<label>` and `<textarea>` for accessibility
* Dropdowns: `<select>` / `<option>`
* Activity Prompt: Create a simple form asking for name and email

---

### **Slide 9: Semantic HTML**

* Tags: `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`
* Benefits:

  * Improves accessibility for screen readers
  * Helps SEO
  * Organizes code logically
* Tip: Always structure content semantically

---

### **Slide 10: Hands-On Project**

* Build a multi-section webpage including:

  * Headings & paragraphs
  * Links & lists
  * Images & forms
  * Semantic layout: header, footer, nav, main
* Encourage creativity and personal content

---

### **Slide 11: Best Practices**

* Use semantic tags for structure
* Write meaningful alt text for images
* Keep code clean and well-indented
* Test in multiple browsers
* Pro Tip: Save frequently and refresh the browser often

---

### **Slide 12: Resources**

* [MDN Web Docs – HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
* Practice Platforms:

  * [CodePen](https://codepen.io/)
  * [JSFiddle](https://jsfiddle.net/)
* Tip: Inspect real websites using DevTools to learn

---

# **HTML 1-Day Crash Course – Learner Guide**

## **Overview**

This guide will help you understand and practice the essentials of HTML. By the end of the day, you will be able to build a small, structured webpage with headings, text, images, links, tables, forms, and semantic layout.

---

## **1. What is HTML?**

* **HTML = HyperText Markup Language**
* **Purpose:** Structure content on the web
* HTML uses **tags** to define elements
  Example: `<p>This is a paragraph.</p>`

---

## **2. Setting Up Your Environment**

1. Install a code editor (VS Code, Sublime Text, or Atom)
2. Create a new file called `index.html`
3. Open it in a browser to see your work

**Basic HTML Structure:**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

---

## **3. Text & Headings**

* **Headings:** `<h1>` to `<h6>` (largest to smallest)
* **Paragraphs:** `<p>`
* **Formatting:**

  * `<strong>` = bold
  * `<em>` = italic
  * `<mark>` = highlight

**Example:**

```html
<h1>My First Webpage</h1>
<p>This is a <strong>bold</strong> word and an <em>italic</em> word.</p>
```

---

## **4. Lists & Links**

**Lists:**

* Unordered list: `<ul>`
* Ordered list: `<ol>`
* List items: `<li>`

**Example:**

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

**Links:**

```html
<a href="https://www.example.com" target="_blank">Visit Example</a>
```

---

## **5. Images & Multimedia**

* **Images:** `<img src="image.jpg" alt="Description">`
* **Audio:** `<audio src="audio.mp3" controls>`
* **Video:** `<video src="video.mp4" controls></video>`

**Tip:** Always include `alt` text for accessibility.

---

## **6. Tables**

* **Structure:**

  ```html
  <table>
    <tr>
      <th>Name</th>
      <th>Age</th>
    </tr>
    <tr>
      <td>Alice</td>
      <td>25</td>
    </tr>
  </table>
  ```

---

## **7. Forms**

* Used to collect user input
* **Common elements:**

  * Text: `<input type="text">`
  * Email: `<input type="email">`
  * Password: `<input type="password">`
  * Submit: `<input type="submit">`
  * Text area: `<textarea>`
  * Dropdown: `<select>` / `<option>`
  * Checkbox / Radio: `<input type="checkbox">`, `<input type="radio">`

**Example:**

```html
<form>
  <label>Name: <input type="text" name="name"></label><br>
  <label>Email: <input type="email" name="email"></label><br>
  <input type="submit" value="Submit">
</form>
```

---

## **8. Semantic HTML**

* Helps structure content meaningfully
* Examples:

  * `<header>` – top of page
  * `<nav>` – navigation
  * `<main>` – main content
  * `<section>` – grouped content
  * `<article>` – standalone content
  * `<aside>` – sidebar
  * `<footer>` – bottom of page

---

## **9. Hands-On Mini Project**

**Objective:** Build a small webpage including:

* Header with title
* Paragraphs about yourself
* A list of hobbies or skills
* Links to your favorite websites
* An image or two
* A contact form
* Footer with copyright

**Tips:**

* Use semantic tags to organize sections
* Indent code for readability
* Save and refresh your browser to check changes

---

## **10. Best Practices**

* Use meaningful `alt` text for images
* Keep your HTML clean and well-indented
* Test in different browsers
* Learn to inspect elements with browser developer tools

---

## **11. Additional Resources**

* [MDN Web Docs – HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
* [CodePen](https://codepen.io/) for live practice

---


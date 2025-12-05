# **Lesson Plan: How the Web Works & HTML Basics (Beginner)**

**Grade / Level:** Beginner / Intro to Web
**Duration:** 50–55 minutes
**Objective:**
Students will understand how the web works and gain practical knowledge of HTML, including page structure, core tags, semantic HTML, multimedia, tables, forms, and CSS styling. By the end of the lesson, students will be able to create a basic webpage with semantic structure, text, images, links, and a simple form.

---

## **Materials Needed**

* Projector or screen for slides
* Web browser (for live demo)
* Code editor (VS Code, Sublime Text, Atom, etc.)
* Sample HTML/CSS files for demonstrations
* Optional: internet connection for live examples

---

## **Lesson Outline**

### **1. Introduction: The Web & the Browser (5 min)**

**Objective:** Understand what happens when a web page loads.

**Activities / Content:**

* Ask: *“What do you think happens when you type a URL into a browser?”*
* Explain key concepts:

  * **Client vs. Server:** Browser requests data; server responds.
  * **URL (Uniform Resource Locator):** Tells the browser where to find resources.
* Visual: Client-server interaction diagram.
* Demo: Open a website and show network requests in DevTools.

---

### **2. Request/Response Cycle & HTTP Basics (5–7 min)**

**Objective:** Understand browser-server communication.

**Content:**

* **HTTP/HTTPS:** Hypertext Transfer Protocol, secure vs non-secure.
* **Status codes:** 200 OK, 404 Not Found, 500 Internal Server Error.
* Importance of HTTPS (encryption).

**Activity / Demo:**

* Use DevTools > Network tab → refresh page → inspect request/response headers and status codes.
* Optional: Compare HTTP vs HTTPS requests.

---

### **3. Introduction to HTML: Structure & Core Tags (10 min)**

**Objective:** Understand basic building blocks of a webpage.

**Content:**

* **HTML:** HyperText Markup Language, structures webpage content.
* Tags, elements, and attributes:

  * Paired tags: `<p>Text</p>`
  * Single tags: `<br>`, `<hr>`, `<img>`
  * Attributes: `src`, `alt`, `href`, `id`, `class`
* Basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Web Page</title>
</head>
<body>
  <h1>Welcome to My Web Page</h1>
  <p>This is a paragraph of text.</p>
</body>
</html>
```

* Headings `<h1>`–`<h6>`, paragraphs `<p>`, and text formatting `<strong>`, `<em>`, `<mark>`.

**Activity / Demo:**

* Edit HTML live in a code editor and refresh the browser.

---

### **4. Lists, Links, and Multimedia (8 min)**

**Objective:** Organize content, create links, and embed multimedia.

**Content:**

* **Lists:** `<ul>` unordered, `<ol>` ordered, `<li>` list items.
* **Links:** `<a href="URL">Clickable text</a>` (internal vs external).
* **Images:** `<img src="image.jpg" alt="Description">`
* **Audio & Video:** `<audio controls>` and `<video controls>`

**Activity / Demo:**

* Embed image, audio, and video in a sample HTML page.
* Inspect elements in the browser.

---

### **5. CSS: Styling Your Page (5 min)**

**Objective:** Understand how CSS works with HTML.

**Content:**

* CSS controls color, fonts, spacing, layout.
* Methods: inline CSS, internal `<style>`, external `<link rel="stylesheet">`.
* Quick demo: change background color or font in DevTools.

---

### **6. Tables & Forms (10 min)**

**Objective:** Structure tabular data and collect user input.

**Tables:**

* Tags: `<table>`, `<tr>`, `<th>`, `<td>`
* Optional attributes: `border`, `colspan`, `rowspan`, `align`

**Forms:**

* Tags: `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`
* Input types: text, email, radio, checkbox, submit, reset
* Accessibility: pair inputs with `<label>`

**Activity / Demo:**

* Create a small form with name, email, gender (radio), favorite color (checkbox), and submit button.

---

### **7. Semantic HTML & Best Practices (5 min)**

**Objective:** Understand semantic structure and accessibility.

**Content:**

* Tags: `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`
* Benefits: accessibility, SEO, maintainable code
* Best practices: meaningful alt text, clean code, test across browsers

**Activity / Demo:**

* Open a sample page showing semantic structure. Discuss navigation and accessibility.

---

### **8. Summary & Review (3–5 min)**

* Recap key points:

  * Browser ↔ Server, HTTP request/response
  * HTML structure, headings, paragraphs
  * Lists, links, images, audio/video
  * Tables and forms
  * CSS styling and semantic HTML
* Quick Q&A: Identify tags and elements on a live website.

---

### **Optional Extension / Homework**

* Build a multi-section HTML page with headings, paragraphs, lists, links, images, forms, and semantic layout
* Inspect request/response in DevTools
* Apply CSS styling

---

## **HTML Crash Course – 1 Day**

**Duration:** ~6–8 hours
**Goal:** Learn core HTML concepts and build a small webpage by the end of the day.

---

### **Morning Session (3–4 hours)**

1. **Introduction & Setup (30 min)**

   * What is HTML and its role
   * Setting up a code editor
   * Creating first HTML file

2. **Basic HTML Structure (30 min)**

   * `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`
   * Title, meta tags, comments

3. **Text & Links (1 hour)**

   * Headings `<h1>`–`<h6>`, paragraphs `<p>`, formatting `<strong>`, `<em>`, `<mark>`
   * Lists `<ul>`, `<ol>`, `<li>`
   * Hyperlinks `<a>` (internal & external)

4. **Hands-on Practice (1 hour)**

   * Build a personal profile page with headings, paragraphs, and links

---

### **Afternoon Session (3–4 hours)**

5. **Images, Multimedia & Tables (1 hour)**

   * Images `<img>` with `src` and `alt`
   * Audio/video embedding
   * Simple tables `<table>`, `<tr>`, `<td>`, `<th>`

6. **Forms (1 hour)**

   * `<form>` and input types: text, email, password, checkbox, radio, submit
   * `<label>`, `<textarea>`, `<select>` / `<option>`
   * Basic form validation

7. **Semantic HTML & Best Practices (30 min)**

   * Tags: `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`
   * Accessibility basics: alt text, labels

8. **Final Hands-on Project (1–1.5 hours)**

   * Build a multi-section webpage with:

     * Headings, paragraphs, images
     * Links and lists
     * A simple form
     * Semantic layout (header, footer, nav, main)

---

**Outcome:**
By the end of the day, learners will have a fully structured HTML page and a solid understanding of core HTML elements used in web development.

---


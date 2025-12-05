# **Lesson Plan: How the Web Works & HTML Basics (Beginner)**

**Grade / Level:** Beginner / Intro to Web
**Duration:** 50–55 minutes
**Objective:** Students will understand how the web works and gain practical knowledge of HTML, including page structure, core tags, semantic HTML, multimedia, tables, forms, and styling with CSS. By the end of the lesson, students will be able to create a basic webpage with semantic structure, text, images, links, and a simple form.

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

**Objective:** Students understand what happens when a web page loads.

**Activities:**

* Ask: *“What do you think happens when you type a URL into a browser?”*
* Explain key concepts:

  * **Client vs. Server**: Browser (client) requests data; server responds.
  * **URL**: Uniform Resource Locator, tells the browser where to find resources.
* Visual: Slide showing client-server interaction diagram.
* Quick demo: Open a website and show network request in DevTools.

---

### **2. Request/Response Cycle & HTTP Basics (5–7 min)**

**Objective:** Students understand how browsers communicate with servers.

**Content:**

* Explain **HTTP/HTTPS**: Hypertext Transfer Protocol, secure vs. non-secure.
* Discuss **status codes**: 200 OK, 404 Not Found, 500 Internal Server Error.
* Highlight encryption importance in HTTPS.

**Activity / Demo:**

* Open DevTools > Network tab. Refresh page. Inspect request/response headers and status codes.
* Optional: Compare HTTP vs HTTPS requests.

---

### **3. Introduction to HTML: Structure & Core Tags (10 min)**

**Objective:** Students understand the basic building blocks of a webpage.

**Content:**

* Define HTML: HyperText Markup Language, used to structure content on webpages.

* Explain tags, elements, and attributes:

  * Paired tags: `<p>Text</p>`
  * Singlet tags: `<br>`, `<hr>`, `<img>`
  * Attributes: `src`, `alt`, `href`, `id`, `class`

* Walk through **basic HTML structure**:

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

* Explain headings `<h1>`–`<h6>`, paragraphs `<p>`, and formatting: `<strong>`, `<em>`, `<mark>`.

**Activity / Demo:**

* Edit HTML live in code editor and refresh browser.

---

### **4. Lists, Links, and Multimedia (8 min)**

**Objective:** Students learn how to organize content, create links, and embed multimedia.

**Content:**

* **Lists**:

  * Unordered `<ul>` & ordered `<ol>` lists
  * List items `<li>`
* **Links**: `<a href="URL">Clickable text</a>`

  * Internal vs external links
* **Images**: `<img src="image.jpg" alt="Description">`
* **Audio & Video**: `<audio controls>` and `<video controls>`

**Activity / Demo:**

* Embed a small image, audio, and video in a sample HTML page.
* Inspect them in the browser and explain attributes.

---

### **5. CSS: Styling Your Page (5 min)**

**Objective:** Students understand how CSS works with HTML to style webpages.

**Content:**

* Explain CSS role: color, fonts, spacing, layout.
* Introduce inline CSS, internal CSS (`<style>`), and external CSS (`link rel="stylesheet"`).
* Quick demo: change background color or font using DevTools.

---

### **6. Tables & Forms (10 min)**

**Objective:** Students learn how to structure tabular data and collect user input.

**Tables:**

* Tags: `<table>`, `<tr>`, `<th>`, `<td>`
* Optional attributes: `border`, `colspan`, `rowspan`, `align`, `cellpadding`, `cellspacing`

**Forms:**

* Tags: `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`
* Input types: text, email, radio, checkbox, submit, reset
* Accessibility: pair inputs with `<label>`

**Activity / Demo:**

* Create a small form with name, email, gender (radio), favorite color (checkbox), and a submit button.
* Show live result in browser.

---

### **7. Semantic HTML & Best Practices (5 min)**

**Objective:** Students understand semantic structure and why it matters.

**Content:**

* Tags: `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`
* Benefits: accessibility, SEO, maintainable code
* Best practices:

  * Meaningful alt text for images
  * Clean, readable code with proper indentation
  * Test across multiple browsers

**Activity / Demo:**

* Open a sample page showing semantic structure and discuss navigation.

---

### **8. Summary & Review (3–5 min)**

* Recap key points:

  * Browser ↔ Server
  * HTTP request/response
  * HTML structure, headings, paragraphs
  * Lists, links, images, audio/video
  * Tables and forms
  * CSS styling and semantic HTML
* Quick Q&A: Ask students to identify tags and elements on a live website.

---

### **Optional Extension / Homework**

* Build a **multi-section HTML page**: headings, paragraphs, lists, links, images, forms, semantic layout
* Inspect request/response in DevTools
* Apply CSS styling

---

✅ **Improvements Made:**

* Clear learning objectives for each section
* More interactive demos and activities
* Expanded HTML content: lists, links, multimedia, tables, forms, semantic HTML
* Beginner-friendly language with teaching cues
* Integrated CSS styling context

---


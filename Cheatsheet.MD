# **HTML & Web Basics – Instructor Cheat Sheet**

---

## **1. The Web & Browser**

**Concepts:**

* **Browser (Client)** → Requests content
* **Server** → Stores content, responds to requests
* **URL** → “Address” of a web resource

**Demo:**

* Open any website → DevTools → Network tab → show requests

**Visual:**

```
Browser ------HTTP/HTTPS------> Server
   <------- Response (HTML, CSS, JS)
```

---

## **2. HTTP Request/Response**

* **Request:** Browser asks for page/resource
* **Response:** Server sends page/resource + status code
* **Status Codes:**

  * 200 → OK
  * 404 → Not Found
  * 500 → Server Error
* **HTTPS:** Secure (encrypted) connection

**Demo:**

* Show DevTools → inspect headers & status codes

---

## **3. HTML Basics**

**HTML Structure:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Page</title>
</head>
<body>
  <h1>Heading</h1>
  <p>Paragraph text</p>
</body>
</html>
```

**Key Tags:**

* **Headings:** `<h1>`–`<h6>`
* **Paragraph:** `<p>`
* **Links:** `<a href="URL">text</a>`
* **Images:** `<img src="file.jpg" alt="desc">`
* **Formatting:** `<strong>`, `<em>`, `<mark>`
* **Lists:** `<ul>`, `<ol>`, `<li>`

**Demo:**

* Edit HTML live → refresh browser

---

## **4. Multimedia**

* **Audio:** `<audio controls src="audio.mp3"></audio>`
* **Video:** `<video controls src="video.mp4"></video>`

**Demo:**

* Embed image/audio/video → show browser rendering

---

## **5. CSS Basics**

* **Purpose:** Styles HTML content (color, font, layout)
* **Methods:**

  * Inline: `<p style="color:red;">Text</p>`
  * Internal: `<style> h1 { color: blue; } </style>`
  * External: `<link rel="stylesheet" href="style.css">`

**Demo:**

* Change font or background color in DevTools

---

## **6. Tables**

```html
<table border="1">
  <tr><th>Name</th><th>Age</th></tr>
  <tr><td>Alice</td><td>25</td></tr>
</table>
```

* Tags: `<table>`, `<tr>`, `<th>`, `<td>`
* Optional: `colspan`, `rowspan`, `align`

---

## **7. Forms**

```html
<form>
  <label>Name: <input type="text" name="name"></label>
  <label>Email: <input type="email"></label>
  <input type="submit" value="Send">
</form>
```

* Tags: `<form>`, `<input>`, `<textarea>`, `<select>`/`<option>`, `<label>`
* Input types: text, email, radio, checkbox, submit

**Demo:**

* Create a simple form → test live in browser

---

## **8. Semantic HTML & Best Practices**

**Semantic Tags:**

* `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`

**Best Practices:**

* Use meaningful alt text for images
* Clean indentation & readable code
* Test across multiple browsers

**Demo:**

* Show a page with semantic layout → point out `<header>`, `<nav>`, `<main>`

---

### **Quick Tips for Live Demos**

1. Use **DevTools Network Tab** for HTTP requests/response
2. Edit HTML/CSS live → refresh to show effect
3. Highlight differences: `<ul>` vs `<ol>`, inline vs internal CSS
4. Keep examples **simple and visible**

---

✅ **Summary Visual Flow:**

```
User types URL
      ↓
Browser (Client)
      ↓ HTTP Request
Server
      ↓ HTTP Response (HTML, CSS, JS, Images)
Browser parses & renders page
```

---

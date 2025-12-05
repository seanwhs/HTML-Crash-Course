# **Learner Guide: How the Web Works & HTML Basics**

## **1. The Web & the Browser**

* **The Web:** A global network of connected computers that share information.
* **Browser (Client):** The program you use to access websites (e.g., Chrome, Firefox, Edge).
* **Server:** The computer that stores webpages and sends them to browsers upon request.
* **URL (Uniform Resource Locator):** The address you type to reach a webpage.

**Key Point:** When you enter a URL, your browser requests a page, and the server sends it back.

**Quick Tip:** Browsers interpret HTML, CSS, and JavaScript to display the page you see.

---

## **2. Request / Response Cycle**

* Browsers and servers communicate using **HTTP** (Hypertext Transfer Protocol).
* **Request:** Your browser asks the server for a page or resource.
* **Response:** The server sends back the requested page or resource.

**Status Codes:**

* `200` → OK (page loaded successfully)
* `404` → Not Found (page doesn’t exist)
* `500` → Server Error (problem on the server side)

**HTTPS:** A secure version of HTTP that encrypts data between browser and server.

**Tip:** Every webpage load may involve multiple request-response cycles for HTML, CSS, images, scripts, and other resources.

---

## **3. HTML — Structure of a Webpage**

* **HTML (HyperText Markup Language):** Defines the content and structure of a webpage.
* **Elements & Tags:** The building blocks of HTML.

**Common Tags:**

| Tag                         | Purpose                        |
| --------------------------- | ------------------------------ |
| `<h1>` – `<h6>`             | Headings (largest to smallest) |
| `<p>`                       | Paragraphs                     |
| `<a>`                       | Links (anchor tag)             |
| `<img>`                     | Images                         |
| `<ul>` / `<ol>` / `<li>`    | Lists (unordered/ordered)      |
| `<form>` / `<input>`        | Forms and input fields         |
| `<table>` / `<tr>` / `<td>` | Tables                         |

**Key Point:** HTML provides the blueprint for your webpage, defining what content exists and how it is structured.

**Tip:** Tags may have **attributes** like `href` (link), `src` (image), `alt` (image description), `type` (input type).

---

## **4. CSS — Style & Presentation**

* **CSS (Cascading Style Sheets):** Adds style and visual design to HTML content.
* CSS controls:

  * Colors, fonts, and text styles
  * Spacing, alignment, and layout
  * Positioning of elements on the page

**How it works:** HTML provides the structure, CSS makes it look good.

**Tip:** Changing CSS only changes the presentation, not the content itself.

---

## **5. How a Page Loads**

1. Browser requests the HTML file from the server.
2. Browser parses the HTML and discovers linked resources (CSS, images, scripts).
3. Browser requests these additional resources from the server.
4. Browser combines all resources and renders the final page for viewing.

**Key Point:** Even though this seems instantaneous, loading a webpage involves multiple sequential steps happening very fast.

---

## **6. Semantic HTML & Best Practices**

* **Semantic Tags:** Provide meaning to your content for accessibility and SEO.

  * Examples: `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`
* **Benefits:**

  * Helps screen readers and assistive technology
  * Improves search engine understanding of your content
  * Makes code organized and maintainable

**Best Practices:**

* Use descriptive `alt` text for images.
* Keep code clean and properly indented.
* Test webpages in different browsers.

---

## **7. Tables & Forms**

**Tables:** Organize data into rows and columns.

* Tags: `<table>`, `<tr>` (row), `<th>` (header), `<td>` (cell)
* Optional attributes: `border`, `colspan`, `rowspan`, `align`, `cellpadding`, `cellspacing`

**Forms:** Collect input from users.

* Tags: `<form>`, `<input>`, `<textarea>`, `<select>`, `<option>`
* Input types: text, email, radio, checkbox, submit, reset
* Pair inputs with `<label>` for accessibility.

**Tip:** Forms and tables are interactive HTML components used for data entry and structured information.

---

## **8. Summary**

* The **browser** connects to a **server** using a **URL**.
* Browser sends an **HTTP request**; server sends an **HTTP response**.
* **HTML** defines content and structure.
* **CSS** styles and layouts the page.
* Semantic HTML improves accessibility and maintainability.
* Browser assembles all resources and renders the final webpage.

---

## **9. Optional Activities**

* Use browser DevTools to inspect a webpage: HTML, CSS, and network requests.

* Create a simple HTML page with:

  * Headings and paragraphs
  * Links and images
  * Lists, forms, and a small table

* Apply CSS to style text, colors, and layout.

* Use semantic HTML tags to structure your page properly.

---


# **HTML 1-Day Crash Course – Lab Guide**

**Objective:** Practice core HTML concepts including text, links, images, lists, tables, forms, and semantic layout.

---

## **Lab 1: Basic HTML Structure (30 min)**

**Tasks:**

1. Create a new file called `index.html`.
2. Add the basic HTML boilerplate:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <!-- Content will go here -->
  </body>
</html>
```

3. Add a `<p>` tag inside `<body>` with text “Hello World!”.

---

## **Lab 2: Text, Headings & Lists (45 min)**

**Tasks:**

1. Add headings `<h1>` to `<h3>` with sample text.
2. Add three paragraphs `<p>` with some text, using `<strong>` and `<em>` for emphasis.
3. Create an **unordered list** of your hobbies.
4. Create an **ordered list** of steps to make tea or coffee.

---

## **Lab 3: Links (30 min)**

**Tasks:**

1. Add a link to your favorite website using `<a href="URL" target="_blank">`.
2. Create an **internal link** to another section in the same page using an `id` attribute.

---

## **Lab 4: Images & Multimedia (30 min)**

**Tasks:**

1. Add an image with `<img src="image.jpg" alt="Description">`.
2. Add an audio file with `<audio src="audio.mp3" controls>`.
3. Add a video file with `<video src="video.mp4" controls></video>`.

---

## **Lab 5: Tables (30 min)**

**Tasks:**

1. Create a table with 3 columns: Name, Age, Profession.
2. Add 2–3 rows of sample data.
3. Highlight the headers using `<th>`.

---

## **Lab 6: Forms (45 min)**

**Tasks:**

1. Create a contact form using `<form>`.

2. Include the following fields:

   * Name (`<input type="text">`)
   * Email (`<input type="email">`)
   * Message (`<textarea>`)
   * Gender (`<input type="radio">`)
   * Subscribe (`<input type="checkbox">`)
   * Submit (`<input type="submit">`)

3. Use `<label>` for each input for accessibility.

---

## **Lab 7: Semantic HTML & Layout (30 min)**

**Tasks:**

1. Restructure your page using semantic tags:

   * `<header>` – for page title and navigation
   * `<nav>` – for menu links
   * `<main>` – for main content
   * `<section>` – for grouped content
   * `<article>` – for individual content blocks
   * `<aside>` – for sidebar
   * `<footer>` – for copyright and contact info

2. Move your previous content into the semantic sections appropriately.

---

## **Lab 8: Final Mini Project (1–1.5 hours)**

**Tasks:**

1. Combine everything learned:

   * Header with a page title and navigation
   * Two or more content sections with headings, paragraphs, lists, and images
   * Table for sample data
   * Contact form
   * Footer with links or copyright

2. Ensure semantic structure and proper indentation.

---

# **HTML 1-Day Crash Course – Lab Solutions**

---

## **Solution 1: Basic HTML Structure**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My Webpage</title>
  </head>
  <body>
    <p>Hello World!</p>
  </body>
</html>
```

---

## **Solution 2: Text, Headings & Lists**

```html
<h1>My Webpage</h1>
<h2>About Me</h2>
<h3>Hobbies</h3>

<p>This is a <strong>bold</strong> word and an <em>italic</em> word.</p>
<p>I enjoy learning <strong>HTML</strong> and <em>CSS</em>.</p>
<p>Practice makes <em>perfect</em>!</p>

<ul>
  <li>Reading</li>
  <li>Coding</li>
  <li>Music</li>
</ul>

<ol>
  <li>Boil water</li>
  <li>Add tea/coffee</li>
  <li>Serve in cup</li>
</ol>
```

---

## **Solution 3: Links**

```html
<p>Visit <a href="https://www.example.com" target="_blank">Example Website</a></p>

<h2 id="contact">Contact Section</h2>
<p>Go to <a href="#contact">Contact Section</a></p>
```

---

## **Solution 4: Images & Multimedia**

```html
<img src="profile.jpg" alt="My Profile Picture">

<audio src="audio.mp3" controls></audio>

<video src="video.mp4" controls width="320" height="240"></video>
```

---

## **Solution 5: Tables**

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>Profession</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
    <td>Developer</td>
  </tr>
  <tr>
    <td>Bob</td>
    <td>30</td>
    <td>Designer</td>
  </tr>
</table>
```

---

## **Solution 6: Forms**

```html
<form>
  <label>Name: <input type="text" name="name" required></label><br>
  <label>Email: <input type="email" name="email" required></label><br>
  <label>Message: <textarea name="message"></textarea></label><br>

  Gender:
  <label>Male <input type="radio" name="gender" value="male"></label>
  <label>Female <input type="radio" name="gender" value="female"></label><br>

  <label>Subscribe: <input type="checkbox" name="subscribe"></label><br>

  <input type="submit" value="Submit">
</form>
```

---

## **Solution 7: Semantic HTML & Layout**

```html
<header>
  <h1>My Webpage</h1>
  <nav>
    <a href="#about">About</a> |
    <a href="#hobbies">Hobbies</a> |
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Me</h2>
    <p>This is a short introduction about myself.</p>
  </section>

  <section id="hobbies">
    <h2>Hobbies</h2>
    <ul>
      <li>Reading</li>
      <li>Coding</li>
      <li>Music</li>
    </ul>
  </section>

  <aside>
    <h3>Sidebar</h3>
    <p>Additional information goes here.</p>
  </aside>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <label>Name: <input type="text" name="name"></label><br>
      <label>Email: <input type="email" name="email"></label><br>
      <input type="submit" value="Submit">
    </form>
  </section>
</main>

<footer>
  <p>&copy; 2025 My Webpage</p>
</footer>
```

---

## **Solution 8: Final Mini Project (Full Example)**

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My HTML Crash Course Page</title>
</head>
<body>

<header>
  <h1>My Webpage</h1>
  <nav>
    <a href="#about">About</a> |
    <a href="#hobbies">Hobbies</a> |
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am a web development beginner learning HTML.</p>
    <img src="profile.jpg" alt="Profile Picture" width="200">
  </section>

  <section id="hobbies">
    <h2>Hobbies</h2>
    <ul>
      <li>Reading</li>
      <li>Coding</li>
      <li>Music</li>
    </ul>
    <ol>
      <li>Wake up</li>
      <li>Code</li>
      <li>Relax</li>
    </ol>
  </section>

  <aside>
    <h3>Sidebar</h3>
    <p>Extra info, links, or announcements.</p>
  </aside>

  <section id="contact">
    <h2>Contact</h2>
    <form>
      <label>Name: <input type="text" name="name"></label><br>
      <label>Email: <input type="email" name="email"></label><br>
      <label>Message: <textarea name="message"></textarea></label><br>
      <input type="submit" value="Submit">
    </form>
  </section>

  <section id="media">
    <h2>Media</h2>
    <img src="image.jpg" alt="Sample Image" width="200"><br>
    <audio src="audio.mp3" controls></audio><br>
    <video src="video.mp4" controls width="320"></video>
  </section>

  <section id="table">
    <h2>Sample Table</h2>
    <table border="1">
      <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Profession</th>
      </tr>
      <tr>
        <td>Alice</td>
        <td>25</td>
        <td>Developer</td>
      </tr>
      <tr>
        <td>Bob</td>
        <td>30</td>
        <td>Designer</td>
      </tr>
    </table>
  </section>
</main>

<footer>
  <p>&copy; 2025 My Webpage</p>
</footer>

</body>
</html>
```


# **Lab: How the Web Works & HTML Basics**

**Level:** Beginner
**Duration:** 60–75 minutes
**Objective:** Students will apply concepts of web structure, HTML, CSS, forms, tables, and multimedia to build a functional webpage.

---

## **Materials Needed**

* Computer with a web browser (Chrome, Firefox, Edge)
* Code editor (VS Code, Sublime Text, Atom)
* Sample images, audio, and video files (optional)
* Internet connection (optional, for reference/demo sites)

---

## **Lab Exercises**

### **Exercise 1: Understanding the Web (10 min)**

**Goal:** Visualize how the browser and server communicate.

**Steps:**

1. Open a web browser and go to any simple website (e.g., example.com).
2. Open **Developer Tools** (F12) → Network tab.
3. Refresh the page. Observe the requests listed: HTML, CSS, images, scripts.
4. Identify at least one **HTTP status code** (200, 404).

**Reflection Questions:**

* What files did the browser request?
* What do the status codes mean?
* How many requests were made to render the page?

---

### **Exercise 2: Basic HTML Structure (15 min)**

**Goal:** Create a simple webpage with headings, paragraphs, and a link.

**Steps:**

1. Open your code editor and create a new file named `index.html`.
2. Add the basic HTML structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My First Webpage</title>
</head>
<body>

</body>
</html>
```

3. Inside `<body>`, add:

* One heading (`<h1>`)
* One paragraph (`<p>`)
* One link (`<a>`) to a website you like

4. Save the file and open it in your browser.

**Optional Challenge:** Add a second paragraph and a subheading `<h2>`.

---

### **Exercise 3: Lists and Multimedia (10 min)**

**Goal:** Add lists, images, audio, and video to your webpage.

**Steps:**

1. Add an **unordered list** (`<ul>`) with 3 items about your favorite hobbies.
2. Add an **ordered list** (`<ol>`) with steps to complete a task (e.g., making tea).
3. Insert an **image** using `<img src="image.jpg" alt="description">`.
4. Add **audio** and **video** elements:

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

<video controls width="320">
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video element.
</video>
```

5. Save and refresh the page to see the multimedia elements.

---

### **Exercise 4: CSS Styling (10 min)**

**Goal:** Apply basic CSS to style your page.

**Steps:**

1. Inside `<head>`, add a `<style>` block:

```html
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 20px;
  }
  h1 {
    color: #0066cc;
  }
  p {
    line-height: 1.5;
  }
</style>
```

2. Save and refresh your page. Observe changes in font, colors, and spacing.
3. Optional: Experiment with `text-align`, `border`, or `padding`.

---

### **Exercise 5: Tables (10 min)**

**Goal:** Create a table displaying data.

**Steps:**

1. Add a table with 3 columns: `Name`, `Age`, `Favorite Color`.
2. Add 3–4 rows of sample data. Example:

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>Favorite Color</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
    <td>Blue</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>22</td>
    <td>Red</td>
  </tr>
</table>
```

3. Save and refresh. Observe the table structure.

---

### **Exercise 6: Forms (10–15 min)**

**Goal:** Create a form to collect user input.

**Steps:**

1. Add a `<form>` inside `<body>`:

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>

  <label>Gender:</label>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br><br>

  <label for="color">Favorite Color:</label>
  <select id="color" name="color">
    <option value="red">Red</option>
    <option value="green">Green</option>
    <option value="blue">Blue</option>
  </select><br><br>

  <input type="submit" value="Submit">
</form>
```

2. Save and open in browser.
3. Optional: Style the form using CSS.

---

### **Exercise 7: Semantic HTML & Page Layout (5 min)**

**Goal:** Organize content using semantic tags.

**Steps:**

1. Wrap your heading in `<header>` and footer content in `<footer>`.
2. Use `<main>` for main content, `<section>` for distinct sections, `<article>` for text blocks.
3. Refresh the page and view the HTML structure using browser DevTools.

---

### **Exercise 8: Reflection & Submission (5 min)**

**Questions:**

1. How did the browser load your webpage? What files were requested?
2. Which HTML elements did you use for structure, content, and multimedia?
3. How did CSS change the appearance of your page?
4. What could you improve to make your page more accessible?

**Submission:**

* Save your `index.html` and any multimedia files used.
* Submit via your classroom platform or USB drive.

---

✅ **Optional Extensions:**

* Add more sections, headings, images, or a navigation menu.
* Link multiple HTML pages together with `<a href="page2.html">`.
* Experiment with advanced CSS (flexbox, grid, hover effects).


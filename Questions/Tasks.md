# HTML & CSS Practice Task

## Task Title
**Build a "Favorite Movie Showcase" Webpage**

---

## Objective
To design and build a fully structured and styled single-page website using semantic HTML5 elements and foundational CSS properties, demonstrating a clear understanding of the CSS Box Model, media embedding, and page layout.

By completing this task, students will practice:
* Structuring a webpage using HTML Semantic tags (`<header>`, `<nav>`, `<section>`, `<footer>`).
* Implementing the CSS Box Model (`margin`, `padding`, `border`, `width`, `height`).
* Creating a styled Navigation Bar with a CSS Dropdown.
* Embedding media using `<iframe>` (YouTube) and `<img>` tags.
* Styling HTML Tables, Forms, Lists, and Text using Internal CSS.

---

# Project Overview
You are hired to create a promotional web page for your favorite movie. The page needs to look visually appealing and well-structured. It will feature a navigation menu, a hero section with a background, an embedded YouTube trailer, a table displaying movie statistics, a list of the main cast, and a form where visitors can "Sign up" to leave a review.

---

# Requirements

**1. HTML Structure & Semantics:**
* Use the standard HTML boiler template (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
* Use semantic tags to divide your page: `<header>`, `<nav>`, at least two `<section>` tags, and a `<footer>`.
* Use appropriate heading tags (`<h1>` to `<h6>`) and paragraphs (`<p>`).
* Use `<div>` and `<span>` tags where appropriate, applying relevant `class` and `id` attributes.

**2. Navigation Bar (CSS):**
* Build a navigation bar inside the `<nav>` tag using an unordered list (`<ul>` and `<li>`) and anchor tags (`<a>`).
* Style the navigation bar to sit horizontally. 
* Implement a simple **CSS Dropdown** menu on one of the navigation links (e.g., "Genres" -> Action, Comedy, Drama).

**3. Media & Visuals:**
* Embed the movie's trailer using an `<iframe>` with a YouTube source.
* Include at least one `<img>` tag with proper `src` and `alt` attributes.
* Use CSS to add a background image to one of your sections (experiment with `background-repeat` and `background-color`).

**4. Data Presentation:**
* Create an Ordered (`<ol>`) or Unordered (`<ul>`) list of the main actors.
* Create an HTML `<table>` showing movie details (e.g., Director, Release Date, Box Office). Style the table using CSS (borders, padding, text alignment).

**5. Form Section:**
* Create a `<form>` inside a section for users to "Register to Review".
* Include `<label>` tags, a text `<input>` (for username), a password `<input>` (for password), and a submit `<button>`.

**6. CSS Styling (Internal CSS):**
* Use **Internal CSS** (`<style>` tag in the `<head>`). Do not use inline styles unless absolutely necessary.
* Apply various CSS Selectors (Element, Class `.`, and ID `#`).
* Manipulate the **Box Model**: explicitly use `margin`, `padding`, `border`, `height`, and `width` on your elements.
* Style your text and fonts (change font-family, color, alignment).
* Style your links (remove default underlines, add hover colors).

---

# Rules

1. **Strictly Allowed Concepts:** You may *only* use HTML tags and CSS properties covered in the Day 1 to Day 6 syllabus. 
2. **No External Frameworks:** Do not use Bootstrap, Tailwind, or external CSS files. All styling must be written by you in the `<style>` tag.
3. **No Advanced Layouts:** Do not use CSS Grid or Flexbox, as they have not been covered yet. Rely on `display` properties (block, inline, inline-block) and the Box Model for layout.
   * **The Catch:** If you choose to use these advanced tools, you must be prepared to confidently explain to your instructor exactly how your code works. No blind copy-pasting allowed! If you use the extra tech, be ready to teach us how you did it. We love seeing learners push their limits!
4. **Commenting:** Include HTML and CSS comments in your code explaining what specific sections do.

---

# Learning Outcome

After completing this task, students will be able to:
1. Translate a blank document into a semantically correct HTML structure.
2. Differentiate between and properly utilize Classes and IDs for CSS targeting.
3. Control the spacing and sizing of web elements confidently using the CSS Box Model.
4. Build interactive, CSS-only components like Navigation bars and Dropdowns.
5. Combine text, tables, forms, and multimedia into a cohesive, styled layout.

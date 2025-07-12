### 0. Introduction & Setup

    - Course Introduction
    - What is HTML? What is CSS?
    - Tools Setup:
        Code Editor (VS Code)
        Browsers (Firefox) & DevTools (Firefox Inspect)
        Live Server Extension
    - First Web Page: Hello World

### 1. Introduction to HTML

1. What is HTML?

   - HyperText Markup Language defines the structure and content of web pages.
   - It is the foundation of all web development.

2. How HTML Works in the Browser

   - Browsers read and render HTML from top to bottom.
   - Tags give structure and meaning to content.

3. HTML vs CSS vs JavaScript

   - HTML: structure
   - CSS: styling
   - JavaScript: behavior

4. HTML Versions and Evolution

   - From HTML4 and XHTML to HTML5
   - HTML5 introduces semantics, media, and better APIs

5. Setting Up Environment
   - Recommended code editors: VS Code, Sublime Text
   - Using Live Server or browser preview

### 2. HTML Document Structure

1. Basic HTML Page Skeleton

   ```html
   <!DOCTYPE html>
   <html>
     <head></head>
     <body></body>
   </html>
   ```

2. Head Section

   - `<title>`, `<meta>`, `<link>`, `<style>`, `<script>`

3. Body Section

   - Visible content goes here

4. HTML Comments
   - Syntax: `<!-- Comment here -->`

---

### 3. Text Formatting and Typography

1. Headings: `<h1>` to `<h6>`
2. Paragraphs: `<p>`
3. Line Breaks and Horizontal Rules: `<br>`, `<hr>`
4. Text Formatting Tags

   - `<strong>`, `<em>`, `<b>`, `<i>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`

5. Preformatted Text and Code Blocks
   - `<pre>`, `<code>`, `<kbd>`

---

### 4. HTML Elements and Attributes

1. Block vs Inline Elements
2. Attributes in HTML

   - Syntax and examples

3. Global Attributes

   - `id`, `class`, `style`, `title`, `hidden`, `contenteditable`, `tabindex`

4. Proper Nesting and Closing of Tags

---

### 5. Hyperlinks and Anchors

1. Basic Anchor Tag: `<a href="">`
2. Absolute vs Relative URLs
3. Opening in New Tabs: `target="_blank"` and `rel="noopener"`
4. Internal Page Links Using IDs

---

### 6. Images and Media

1. The `<img>` Tag

   - `src`, `alt`, `width`, `height`

2. Image Formats: JPG, PNG, SVG, WebP
3. Responsive Image Practices
4. `<figure>` and `<figcaption>`
5. Audio and Video Tags

   - `<audio>`, `<video>` with `controls`, `autoplay`, `muted`, `poster`

---

### 7. Lists

1. Ordered List: `<ol>`
2. Unordered List: `<ul>`
3. List Items: `<li>`
4. Nested Lists
5. Description List: `<dl>`, `<dt>`, `<dd>`

---

### 8. Tables

1. Table Elements

   - `<table>`, `<tr>`, `<td>`, `<th>`

2. Table Sections

   - `<thead>`, `<tbody>`, `<tfoot>`

3. Attributes

   - `colspan`, `rowspan`, `scope`, `headers`

4. Semantic Use and Accessibility Considerations

---

### 9. Forms and Input Elements

1. `<form>` Tag Basics

   - `action`, `method`, `enctype`

2. Common Input Types

   - `text`, `email`, `password`, `number`, `url`, `tel`, `search`, `file`, `date`

3. Radio Buttons and Checkboxes
4. Textarea and Button Elements
5. Dropdowns with `<select>` and `<option>`
6. Label Association with Inputs

   - `<label for="">`

7. Input Attributes

   - `required`, `readonly`, `disabled`, `min`, `max`, `placeholder`, `pattern`, `autocomplete`

---

### 10. Semantic HTML

1. What is Semantic HTML?

   - Tags that describe the meaning of content

2. Common Semantic Elements

   - `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<nav>`

3. Comparison with Non-semantic Tags

   - `<div>`, `<span>`

4. Benefits for SEO and Accessibility

---

### 11. HTML Entities and Symbols

1. Purpose of HTML Entities
2. Common Entities

   - `&lt;`, `&gt;`, `&copy;`, `&amp;`, `&nbsp;`, `&quot;`

3. Currency Symbols, Emojis, and Special Characters

---

### 12. HTML Meta Tags

1. What are Meta Tags?
2. Essential Meta Tags

   - `charset`, `viewport`, `description`, `keywords`, `author`

3. SEO and Social Sharing

   - `robots`, `canonical`, `og:title`, `og:image`

---

### 13. Embedding and Iframes

1. Embedding Content with `<iframe>`
2. Common Uses: YouTube, Google Maps, PDFs
3. Attributes: `src`, `width`, `height`, `allowfullscreen`, `sandbox`, `referrerpolicy`

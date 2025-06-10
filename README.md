# HTML-Documentation

📄 HTML Documentation
This repository serves as a comprehensive and beginner-friendly guide to HTML (HyperText Markup Language), the foundational language for building web pages. Here, you'll find clear explanations, practical code examples, and visual outputs to help you understand and apply HTML concepts effectively.
📚 Table of Contents
 * Introduction to HTML
 * Basic HTML Structure
 * HTML Headings
 * HTML Paragraphs
 * HTML Links
 * HTML Images
 * HTML Lists
 * HTML Tables
 * HTML Forms
 * HTML Semantic Elements
 * HTML Multimedia
 * Advanced HTML Features
 * Learning Resources
 * Contribution
🧭 Introduction to HTML
HTML (HyperText Markup Language) is the foundation of all web pages. It structures content using a system of elements and tags, allowing browsers to interpret and display it correctly.
🏗️ Basic HTML Structure
Every HTML document starts with a <!DOCTYPE html> declaration and follows this basic layout:
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>My First Heading</h1>
    <p>My first paragraph.</p>
</body>
</html>

What you'll see in the browser:
 * A large heading that says "My First Heading" followed by a line of text that says "My first paragraph."
 * The browser tab or window title bar will display "Page Title".
🔠 HTML Headings
Headings range from <h1> (most important) to <h6> (least important), providing structure and hierarchy to your content.
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h3>Heading 4</h3>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

What you'll see in the browser:
 * Six lines of text, each appearing as a heading. "Heading 1" will be the largest, with each subsequent heading ("Heading 2" through "Heading 6") appearing progressively smaller.
📄 HTML Paragraphs
Paragraphs are enclosed in <p> tags, used for blocks of text.
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

What you'll see in the browser:
 * Two separate lines of text, "This is a paragraph." and "This is another paragraph.", with a visible space between them (the default browser styling for paragraphs).
🔗 HTML Links
Create hyperlinks using the <a> tag and href attribute to navigate to other pages or resources.
<a href="https://www.example.com">Visit Example.com</a>

What you'll see in the browser:
 * The text "Visit Example.com" rendered as a clickable link, typically underlined and blue (by default). Clicking it will take you to https://www.example.com.
🖼️ HTML Images
Embed images using the <img> tag with src (source) and alt (alternative text) attributes. width and height control dimensions.
<img src="image.jpg" alt="Description of image" width="500" height="600">

What you'll see in the browser:
 * An image displayed with a width of 500 pixels and a height of 600 pixels.
 * If the image.jpg file isn't found or fails to load, you'll see the text "Description of image" in its place.
📋 HTML Lists
HTML supports three types of lists to organize content:
Unordered List (<ul>) - for items without a specific order:
<ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ul>

Ordered List (<ol>) - for items with a specific sequential order:
<ol>
    <li>First item</li>
    <li>Second item</li>
    <li>Third item</li>
</ol>

Description List (<dl>) - for terms and their descriptions:
<dl>
    <dt>Coffee</dt>
    <dd>- black hot drink</dd>
    <dt>Milk</dt>
    <dd>- white cold drink</dd>
</dl>

What you'll see in the browser:
 * Unordered List: A list of items (Coffee, Tea, Milk) each preceded by a bullet point.
 * Ordered List: A list of items (First item, Second item, Third item) each preceded by a number (1., 2., 3.).
 * Description List: The terms "Coffee" and "Milk" followed by their corresponding descriptions ("- black hot drink" and "- white cold drink"), with the descriptions typically slightly indented.
🧾 HTML Tables
Tables structure data using <table>, <tr> (table row), <th> (table header), and <td> (table data) tags.
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>John</td>
        <td>30</td>
    </tr>
    <tr>
        <td>Jane</td>
        <td>25</td>
    </tr>
</table>

What you'll see in the browser:
 * A grid-like structure displaying data. The top row will have "Name" and "Age" as bolded headers. Below that, "John" will be in the first column and "30" in the second, followed by "Jane" and "25" on the next row.
📨 HTML Forms
Forms collect user input using various controls like text fields, buttons, and more.
<form action="/submit" method="post">
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname"><br>
    
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname"><br>
    
    <input type="submit" value="Submit">
</form>

What you'll see in the browser:
 * The text "First name:" followed by an empty box (a text input field).
 * Below that, "Last name:" followed by another empty box.
 * Finally, a clickable button labeled "Submit". You can type text into the boxes before clicking the button.
🧩 HTML Semantic Elements
Semantic elements give meaning to your layout, improving accessibility and SEO by describing the purpose of content sections.
<header>
    <h1>Website Title</h1>
</header>

<nav>
    <a href="/html/">HTML</a> |
    <a href="/css/">CSS</a> |
    <a href="/js/">JavaScript</a>
</nav>

<section>
    <h2>Section Heading</h2>
    <p>Section content...</p>
</section>

<footer>
    <p>Footer information</p>
</footer>

What you'll see in the browser:
 * A main heading "Website Title" at the top (within the header area).
 * Below that, a navigation bar with clickable links for "HTML", "CSS", and "JavaScript".
 * Then, a section with a subheading "Section Heading" and some paragraph text "Section content...".
 * At the bottom of the page, a footer area containing "Footer information". While not visibly distinct by default, these elements provide structure for assistive technologies and search engines.
🎵 HTML Multimedia
HTML allows embedding audio and video directly into web pages.
Audio
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

Video
<video width="320" height="240" controls>
    <source src="movie.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

What you'll see in the browser:
 * Audio: A media player control (typically a bar with play/pause, volume, and progress) that allows you to play the audio.mp3 file. If the browser can't play it, you'll see "Your browser does not support the audio element."
 * Video: A video player showing the movie.mp4 file, with play/pause, volume, full-screen, and progress controls, sized at 320 pixels wide by 240 pixels tall. If the browser can't play it, you'll see "Your browser does not support the video tag."
🧠 Advanced HTML Features
Explore more dynamic and interactive capabilities of HTML5.
HTML5 Canvas
The <canvas> element provides a drawing surface for 2D graphics using JavaScript.
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"></canvas>

<script>
    var c = document.getElementById("myCanvas");
    var ctx = c.getContext("2d");
    ctx.fillStyle = "#FF0000";
    ctx.fillRect(0, 0, 150, 75);
</script>

What you'll see in the browser:
 * A white rectangular area (200x100 pixels) with a thin black border. Inside this area, a solid red rectangle (150x75 pixels) will be drawn in the top-left corner.
SVG Graphics
Scalable Vector Graphics (<svg>) are XML-based vector graphics that scale without losing quality.
<svg width="100" height="100">
    <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

What you'll see in the browser:
 * A perfectly round yellow circle with a thick green border, appearing within a 100x100 pixel area. This graphic will remain sharp and clear even if scaled up or down.
📖 Learning Resources
To deepen your HTML knowledge, we recommend these trusted resources:
 * MDN Web Docs (HTML) — Comprehensive, developer-friendly resource.
 * W3Schools HTML Tutorial — Beginner-friendly reference and examples.
 * HTML Living Standard (WHATWG) — The official HTML specification.
🤝 Contribution
Suggestions, corrections, and additions are always welcome! Let's make this documentation even better together.
Feel free to:
 * Submit a pull request with your proposed changes.
 * Open an issue to report errors or suggest new ideas.

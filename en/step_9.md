## Make your page responsive

CSS can be used to make your webpage responsive when viewed on different devices.

--- collapse ---

---
title: What does responsive mean?
---

Webpages can be viewed on many different devices and should be **responsive** to each device. This means that if a user views your page on a mobile phone, it should respond to a smaller screen and if they view it on a desktop PC, it should respond to a larger screen. 

--- /collapse ---

--- task ---

Find the **second** `<section>`. 

Add `class="wrap"` to the `<section>` tag.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 40
---
    <!-- The first drawing and instructions go here -->
    <section class="wrap">
      <img src="love.png" alt="The love facial expression.">
      <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
    </section>

--- /code ---

--- /task ---

You can also add coloured borders in different styles to HTML elements. The `dashed-border` class in the style file creates a dashed border. 

--- task ---

Add the `dashed-border` class to the `<img>`. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- The first drawing and instructions go here -->
    <section class="wrap">
      <img class="dashed-border" src="love.png" alt="The love facial expression.">
      <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
    </section>

--- /code ---

--- /task ---

You can make the corners of an element rounded with the `rounded` class. 

--- task ---

Add the `rounded` class to the `<img>`. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 41
---
    <!-- The first drawing and instructions go here -->
    <section class="wrap">
      <img class="dashed-border rounded" src="love.png" alt="The love facial expression.">
      <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
    </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

Drag the bar between the text editor and your webpage to make the webpage narrower. 

The text should move below the image. This is the layout for users who view the webpage on a mobile phone. 

Drag the bar back after you test it, so you can see the image and text side-by-side. 

![In the Editor, the vertical space between the two panes is dragged from left to right to show that the webpage adjusts for smaller screens.](images/drag-window.gif)

--- /task ---

## Style with classes

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

This step shows you how to add classes to customise the styles on your page. 

</div>
<div>
<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-8-simplified" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

--- collapse ---

---
title: How do CSS classes work?
---

If you want to apply styling to specific elements, you can create a **class** in a CSS file. You can then add a `class=` **attribute** to an element in your HTML code to let the browser know what styling should be applied. 
  
The class styling overrides any element styling that has already been applied. Notice that the changes take place as you add the classes to your code.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---

.hugefont {
  /* Used to make a large emoji */
  font-size: 6rem;
  text-align: center;
  padding: 1rem;
}

--- /code ---

--- /collapse ---

--- task ---

Your CSS file has a custom CSS class called `border-bottom`. 

This class adds a thick, solid-coloured line border to the bottom of any HTML element that uses it.

Go to your `index.html` file and find your `header`. 

Add `class="border-bottom"` after the word `header` in your `header` tag. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---
  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom">
      <h1>Draw anime with me</h1>
    </header>

--- /code ---

--- /task ---

--- task ---

Add the `border-top` class to your `footer` code to apply a thick border to the top of your footer. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- web page footer -->
    <footer class="border-top">

--- /code ---

--- /task ---

The `primary` class sets a contrasting background and text colour for most of the main content. 

The `secondary` and `tertiary` classes set additional colour combinations that look good with the colours in the `primary` class.

--- task ---

Add the `secondary` class to your `footer` code to apply a different colour background to your footer. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 55
line_highlights: 56
---
    <!-- web page footer -->
    <footer class="border-top secondary">

--- /code ---

--- /task ---

--- task ---

Add `class="primary"` to `<main>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 34
---
    <!-- The main content for the web page goes between the main tags -->
    <main class="primary">

--- /code ---

--- /task ---

--- task ---

Add `secondary` to `<header>`.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 29
---
    <!-- The page header code goes here -->
    <header class="border-bottom secondary">

--- /code ---

--- /task ---

The `xcenter` class in your CSS file aligns items horizontally across the page. 

--- task ---

Add `class="tertiary"` to the **first** `<section>` element.

Also, add `class="xcenter"` to the `<p>` in the same section. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35, 37
---
    <!-- The main content for the web page goes between the main tags -->
    <main class="primary">
      <section class="tertiary">
        <h2>Facial expressions</h2>
        <p class="xcenter">Take a look at these facial expressions and try them in your own drawings.</p>
      </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

You should see the changes from adding the classes to your web page.

--- /task ---

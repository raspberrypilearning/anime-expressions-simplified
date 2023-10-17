## Add content to your webpage

On your webpage, the main content is broken down into **sections**.

Place main content between the `<main>` tags.  

--- task ---

Add `<section></section>` tags between the `<main>` tags. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 35-37
---
    <!-- The main content for the webpage goes between the main tags -->
    <main>
      <section>

      </section>
        <!-- The first drawing and instructions go here -->  

--- /code ---

--- collapse ---

---
title: Tip on adding more tags to a section
---
As you build your webpage, you will add other tags inside your section. Position your cursor between the `<section>` and `</section>` tag, then press Enter on your keyboard to split the tags across multiple lines. 

--- /collapse ---

--- /task ---

--- task ---

Add the subheading tags `<h2>` between the `<section>` tags.

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 36
---
    <!-- The main content for the webpage goes between the main tags -->
    <main>
      <section>
        <h2></h2>
      </section>
        <!-- The first drawing and instructions go here --> 


--- /code ---

--- /task ---

--- task ---

Now enter the subheading text `Facial expressions` between the `<h2>` tags. Your code should look like this:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 36
---
    <!-- The main content for the webpage goes between the main tags -->
    <main>
      <section>
        <h2>Facial expressions</h2>
      </section>
        <!-- The first drawing and instructions go here --> 

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

The text on your webpage should be slightly smaller than the big heading above with bold styling. 

This is because `<h2>` is a smaller heading than `<h1>`.

--- /task ---
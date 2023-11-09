## Style an image

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

This step shows you how to add classes to style an image on your page.

</div>
<div>
<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-9-simplified" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

You can add coloured borders in different styles to HTML elements. The `dashed-border` class in the style.css file creates a dashed border. 

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
    <section>
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
    <section>
      <img class="dashed-border rounded" src="love.png" alt="The love facial expression.">
      <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
    </section>

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

You should see the changes from adding the classes to your web page.

--- /task ---

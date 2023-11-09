## Add a facial expression

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
In this step, add the first drawing and instruction to your web page.
</div>
<div>
<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-5-simplified" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

--- task ---

Find the comment `<!-- The first drawing and instructions go here -->`.

Add in the `<section></section>` tags for your first drawing and instruction content. 

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 40-42
---
    <main>
      <section>
        <h2>Facial expressions</h2>
        <p>Take a look at these facial expressions and try them in your own drawings.</p>
      </section>
       
      <!-- The first drawing and instructions go here -->     
      <section>
          
      </section> 

--- /code ---

--- /task ---

Your starter project contains images to use in this project. 

Add the image called `love.png` to your web page.

--- task ---
Inside your new section, add an `<img>` tag to display an image. The `src` **attribute** gives the name of the image.

 The `<img>` tag doesn't have an end tag.
 
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
        <img src="love.png">
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

The `love.png` image appears on your web page.

--- /task ---

--- task ---

Add the `alt` attribute to provide alternative text for people who cannot view the image. 

You can copy the description of your image and paste it into your code: `A line drawing of a smiling character with hearts for eyes.`

--- collapse ---

---
title: What is alt text?
---

**Alternative (Alt) text** is a description of an image and is important in accessible web design to describe images to people who are unable to see them. The text does not appear on the web page but it is read aloud by screen readers.

--- /collapse ---

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
        <img src="love.png" alt="A line drawing of a smiling character with hearts for eyes.">
      </section> 

--- /code ---

--- /task ---

--- task ---

Add a paragraph of text in `<p></p>` tags to describe how to draw the love anime facial expression. 

You can copy the paragraph and paste it into your code: `<p>To make your anime character look like they are in love, replace the eyes with rounded hearts. You can add three more hearts inside for a fun effect.</p>`

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- The first drawing and instructions go here -->     
      <section>
        <img src="love.png" alt="A line drawing of a smiling character with hearts for eyes.">
        <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
      </section> 

--- /code ---

--- /task ---

The `<strong>` tag makes important text **bold**.

--- task ---

Add `<strong>` tags around the word 'love':

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 39
line_highlights: 42
---   
      <!-- The first drawing and instructions go here -->     
      <section>
        <img src="love.png" alt="A line drawing of a smiling character with hearts for eyes.">
        <p>To make your anime character look like they are in <strong>love</strong>, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
      </section> 

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

The instructions appear below your image and the word **love** is in bold. 

<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-5-simplified" width="500" height="750" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
--- /task ---


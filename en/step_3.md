## Add the first section in your main content

Any main content should be placed between the `<main>` tags. On your webpage, the main content is broken down into **sections**. 

--- task ---

Your webpage needs an introduction section. Add `<section></section>` tags between the `<main>` tags. 

**Tip:** As you build your webpage, you will add other tags inside your section. Position your cursor between the `<section>` and `</section>` tag, then press Enter on your keyboard to split the tags across multiple lines. 

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

--- /task ---

--- task ---

You are now going to add a subheading within the section that you have just created.

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

Notice how the text on your webpage is slightly smaller than the big heading above and has bold styling. This is because `<h2>` is a smaller heading than `<h1>`.

--- /task ---

--- task ---

You are now going to add a paragraph of text as an introduction to your anime webpage. 

Underneath your `<h2>` heading code, add the paragraph `<p>` tags. 

  --- code ---
  ---
  language: html
  filename: index.html
  line_numbers: true
  line_number_start: 33
  line_highlights: 37
  ---
    <!-- The main content for the webpage goes between the main tags -->
    <main>
      <section>
        <h2>Facial expressions</h2>
        <p></p>
      </section>
        <!-- The first drawing and instructions go here --> 

--- /code ---

--- /task ---

--- task ---

Between the `<p>` tags, you need to add in this introductory text:

`Take a look at these facial expressions and try them in your own drawings.`

**Tip:** You can highlight the text above and then right-click (tap and hold on mobile) and choose 'Copy'. Then click between the `<p>` tags in your code and then right-click and choose 'Paste'.

Your code should look like this:

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 33
line_highlights: 37
---
    <!-- The main content for the webpage goes between the main tags -->
    <main>
      <section>
        <h2>Facial expressions</h2>
        <p>Take a look at these facial expressions and try them in your own drawings.</p>
      </section>
        <!-- The first drawing and instructions go here --> 

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

The text appears under the subheading and uses the default paragraph styling. 

Well done! Your page now has a header, a subheading, and an introductory paragraph. 

![alt=""](images/step2-output.PNG)

--- /task ---

## Save your project

Your project is saved automatically. Return to the starter link in the same web browser to see your changes. 

--- collapse ---

---
title: I accidentally closed my project
---

Click on the [starter project](https://staging-editor.raspberrypi.org/en/projects/anime-expressions-starter){:target="_blank"} link to open your project. Use the same web browser to see your changes.

--- /collapse ---

--- collapse ---

---
title: If you have a Code Editor account
---

Click the 'Save' button to create a copy of the project in your Raspberry Pi account.

--- /collapse ---

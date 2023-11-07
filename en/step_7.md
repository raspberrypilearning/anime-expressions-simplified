## Edit your CSS style sheet

You can make changes to your style sheet to style your content.

--- task ---

Click on the `Project files` icon in the Code Editor then select the `style.css` file top open in in a new tab.

![The Code Editor with the Project files icon highlighted](images/select-file.png)

![The Code Editor with the style.css file highlighted](images/select-style.png)

This CSS file contains all of the CSS for your project. You will find out about some key parts of this CSS file as you create your webpage.

When you add CSS styling to an **element**, it applies that styling to every single element on the page that has the same tag. 

**Find:** Scroll down and find the rule that controls the style of the `<h2>`. 

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 109-113
---  

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: left; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

--- /code ---

This rule states which font should be used, how the text should be aligned, and how much space should be around the header. 

--- /task ---

--- task ---

At the moment, the `<h2>` heading is aligned to the left.

Change the `text-align` property of the `h2` rule to `center`.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 111
---  

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: center; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

--- /code ---

--- /task ---

--- task ---

**Test:** Click the **Run** button. 

Look at your webpage and make sure the 'Facial expressions' text is centred. 

**Debug:** Check the spelling of the word `center`. HTML uses American (US) English spelling. 

<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-6-simplified" width="350" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

--- /task ---


## Style your page

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

This step shows you how to use CSS to change the colours, fonts, and layout on your webpage.   
  
</div>
<div>
<iframe src="https://staging-editor.raspberrypi.org/en/embed/viewer/anime-expressions-step-4" width="500" height="400" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>
</div>
</div>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
<span style="color: #0faeb0">**Cascading Style Sheets (CSS)**</span> is the language that you use to tell the web browser exactly how your webpage should look, which includes the positioning, colours, and fonts. We call this the style.
</p>

Every **rule** in CSS is made up of two parts: the **selector** and the **declaration**.

The **selector** is the part of HTML that you want to style. In this example it is `h1`. 

<div style="background-color:#2d2d2d; padding: 1em;">
  <pre><span style="color:#000; background-color:#d2d2d2; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">h1 </span
  ><span style=" color:#ccc;  font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">{
  color: blue;
  font-size: 12px;
}</span></pre>
</div>
<br/>

The **declaration** is in curly brackets `{}`. It gives instructions of the styles that should be used. 

<div style="background-color:#2d2d2d; padding: 1em;">
<pre><span style="color:#ccc; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">h1 </span
><span style=" color:#000; background-color:#d2d2d2; font-family: Consolas, Monaco, 'Andale Mono', 'Ubuntu Mono', monospace; font-size: 1em">{
  color: blue;
  font-size: 12px;
}</span></pre>
</div>
<br/>

### Link the CSS file

The starter project includes CSS files, which contain a set of useful rules. 

--- task ---

Unfold the `<head>` section of your code so that you can view the code inside it.

![The mouse clicks on the little triangle next to the line 3 number to collapse the head code.](images/step_2_collapse.gif)

--- /task ---

--- task ---

At the bottom of your `<head></head>` section, remove the `<!--` and `-->` arrows from the start and end of both lines of link code:

**Before**

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
---   
    <!-- Include CSS style file -->

    <!-- <link href="style.css" rel="stylesheet" type="text/css" /> -->
    <!-- <link href="candy.css" rel="stylesheet" type="text/css" /> -->
  </head>

--- /code ---

**After**

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
---   
    <!-- Include CSS style file -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="candy.css" rel="stylesheet" type="text/css" />
  </head>

--- /code ---
--- /task ---

--- task ---

**Test:** Click the **Run** button. 

Take a look at your webpage in the right-hand pane. Notice that the styles and layout of your output has now changed. 

--- collapse ---

---
title: Quick tips
---

+ To collapse the `<head>` section after you have seen the change, click the arrow next to it. 
+ HTML elements have default browser styles that you have seen as you have written your HTML code. 

--- /collapse ---

--- /task ---

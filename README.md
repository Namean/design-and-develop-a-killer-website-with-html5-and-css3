<script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
<style>

  /* [::COLOR-PALETTE::]*/
  :root {
    --white: #C4BEDE;
    --light-green: #7CD828;
    --green: #A8DA1C;
    --purple: #A35CDC;
    --yellow: #F5B93D;
    --black: #1C1A26;
    --light-grey: #2F2B3E;
    --medium-grey: #292435;
    --dark-grey: #221E2C;
    --light-black: #1b1a26;
    --black: #181620;
  }

  /* [::ELEMENTS::] */

  body {
    background-color: var(--light-black);
    color: white;
    font-family: sans-serif;
    font-weight: 400;
    font-size: 120%;
  }

  header {}

  p {
    color: red;
    text-align: justify;
  }

  /* [::HEADINGS::] */

  h1 {
    color: var(--green);
    font-size: 250%;
    /* text-shadow: 1px 1px 2px var(--white-text); */
    text-shadow: var(--green-text) 1px 0 10px;
  }

  h3 {
    text-align: center;
    color: var(--green);
    font-size: 150%;
    border: solid 3px white;
    text-align: center;
    padding: 20px;
    text-transform: capitalize;
  }

/* [::LINKS::] */
  a,
  a:hover {
    color: var(--purple-text);
    text-decoration-color: var(--green);
  }

  li a { color: var(--purple) }

  

  .section-list {}
  .section-list li {
    list-item: none;
  }

  .container {
    padding: 15px;
  }

/* [::CUSTOM-CLASSES::]*/
 .list {}

 .list li {
  position: relative;
  margin: 0 auto;
  left: 300px;
  display: inline-block;
  text-transform: uppercase;
  text-align: center;
  color: var(--yellow);
  font-size: 200%;
 }

 .list li::after {
    color: white;
    content: ""
 }

.list li:last-child:after { content: ""; }



  </style>

<!-- # <h5 style="display: none">design-and-develop-a-killer-website-with-html5-and-css3</h5> -->
<div class="container">
  <header>
    <h1 style="text-align: center; border: solid 3px white; padding: 20px">
        Build Responsive Real-World Websites with HTML and CSS
      </h1>
      <p style="text-align: center; text-transform: uppercase; color: var(--white)">
        Learn modern HTML5 CSS3 and web design by building a stunning website for your portfolio!
        Includes flexbox and CSS Grid
      </p>
<ul class="list">
  <li>modern web design</li>
</ul>
<h2>
  This course is all about building beautiful and responsive websites
</h2> 
</header>

<div class="spacer" style="height: 150px"></div>

<h3>How the course is organized and structured</h3>

<p style="margin-top: 20px">
This course is divided into 9 sections, 35+ hours of content!
</p>
<ul class="section-list">
  <li><a href="">Section 01 welcome and first steps</a></li>
  <li><a href="">Section 02 html fundamentals</a></li>
  <li><a href="">Section 03 css fundamentals</a></li>
  <li><a href="">Section 04 building layouts</a></li>
  <li><a href="">Section 05 web design framework</a></li>
  <li><a href="">Section 06 components and layouts</a></li>
  <li><a href="">Section 07 omnifood: desktop</a></li>
  <li><a href="">Section 08 omnifood: responsive</a></li>
  <li><a href="">Section 09 omnifood optimizations</a></li>
</ul>

<p style="text-align: justify;">
In section 1 you'll build your first web page, then in section 2 we'll learn about the basics of the HTML language. Later in section 3 we'll learn the foundations of css:
</p>

- styling text
- css box-model
- sizing and positioning elements

<p style="color: var(--yellow)">
We'll event build some developer skills such as reading documentation and debugging
section 4 is all about building layouts how to arrang eelements on the page in a logical ways
we can do that in multiple ways in CSS, wel'' focus on modern tech like flexbox and css grid</p>

<p>In Section 5 we move on to web design, which could be an entire course by itself, design guidelines to build interfaces and make them beautufiul and professional looking.</p>

<p>
Section 6 covers ommon website components, and layout patterns that common websites use. Which you'll build into your own website using these components yourself.
</p>

<p>
Finally, sections 7 through 9 are about building our capstone project a beautiful, and responsive real world website called <strong style="color: var(--green)">Omnifood</strong>, during the project use'll use all the skills that you've accumulated over the course.</p>
<p>
Covering  planing and sketching a website, and how to handle a big project from start to finish. By the end of the course you'll be able to design and build something like this by yourself!
</p>
<p>
There will be coding challneges, and the HTML and CSS skills, practicing is the single most important thing that you need to do to learn coding.
</p>

<p>
I hope that you'll have a ton of fun with the course, aand you'll have a succesful start with your webdevelopment carreer.
</p>

### Lesson 2. Read Before you start

<input type="checkbox">
<label>Download the starter code</label>

[Starter and final code and FAQs on GitHub](https://github.com/jonasschmedtmann/html-css-course)

### 3. Migration Guide to v2

Just go through the new content, but the old content is available in Section 11 [LEGACY] Old Course Version 1

### 4. A High-Level Overview of Web Development

Covers client server architecture

### 5. Setting Up Our Code Editor

Download vscode

install prettier

- vscode -> settings (search: default formatter) := prettier
- vscode -> settings (search: format on save) := checked
- vscode -> settings (search: Auto Save) := onFocusChange
- vscode -> settings (search: tab size) := 2

</div>

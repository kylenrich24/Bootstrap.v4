# Bootstrap.v4 🚀
<img src="https://blog.templatetoaster.com/wp-content/uploads/2019/09/What-is-Bootstrap-Facebook.png" height="500" width="1000">
<p>Bootstrap is an HTML, CSS and JS framework for developing responsive, mobile-first projects on the web 🎉🎉🎉 .</p>
<p>DOCS: https://getbootstrap.com/docs/4.3/components/alerts/ 📋</p>
<p>There are 2 ways to use Bootstrap 🔧:</p>
<ul>
<li>☝️Download the files and it to your application</li>
  <ol>
    <li>Download the files https://getbootstrap.com/docs/4.3/getting-started/download/</li>
    <li>We need <em>bootstrap.css</em> or <em>bootstrap.min.css</em> from <em>/css/css/bootstrap.css</em></li>
    <li>Copy and paste this to the same directory where your app is in</li>
    <li>Link using a stylesheet link tag</li>
  </ol>
<li>☝️Link CDN</li>
  <ol>
    <li>Link the CSS cdn into the head of your HTML doc </li>
     <li>Link the JS cdn into the script before closing the body tag</li>
</ul>
    </ol>
  <br>
 
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
   <br>
   <pre><code>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
   </code></pre>
<br><br<
<p><strong>We can now start using Bootstrap components by adding classes to our elements</strong><p>
<hr>

<br>
<br>

<h2>⚡️Differences from v3</h2>
<ul>
<li>Syntax has been majorly changed. Refer to DOCS.</li>
<li>Flexbox is enabled by default</li>
<li>Switched from px to rem as our primary CSS unit. It is a relative unit that allows you to scale to size things in our web app based on the <strong>Global font-size</strong> which is 16px</li>
<li>There is now a fifth tier in the Grid System. We have xs, sm, md, lg, xl </li>
  <li>Added dozens of new utility classes for common CSS propery-value pairs and margin/padding spacing shortcuts</li>
  <li>Upgraded class names in Grid System</li>
  <li>New Cards component</li>
  <li>No more Glypichons. Use Font Awesome</li>
  <li>Renamed btn-default to btn-primary</li>
  <li>No more .btn-xs</li>
</ul>

<br>
<br>
<h2>⚡️Colors and Backgrounds</h2>
<br>
<p>Bootstrap takes advantage of Contextual Colours</p>
<br>
<h3>Bootstrap Colour List</h3>
<img src="https://bootstrap.themes.guide/assets/howto/colors.png" width="500px" height="180">

<h3>Text Colours</h3>
<img src="https://www.jquery-az.com/wp-content/uploads/2018/01/15-3-Bootstrap-link-colors.png" width="200px" height="180">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20190426131212/background_color_list.png" width="400px" height="180">

<br>
<br>

<h2>⚡️Typography</h2>
<br>
<h3>Display</h3> - acts like header tag, but are significantly bigger
<br>
<img src="https://www.tutorialrepublic.com/lib/images/bootstrap-4/bootstrap-display-headings.png" width="400px" height="180">

```html
<h1 class="display-1">Display Heading 1</h1>
<h1 class="display-2">Display Heading 2<</h1>
<h1 class="display-3">Display Heading 3<</h1>
<h1 class="display-4">Display Heading 4<</h1>
```
<br>
<br>
<h3>Blockquotes</h3>
<br>
<img src="https://i.stack.imgur.com/Lyfta.png" width="350" height="100">

```html
<blockquote class="blockquote">
  <p>Lorem Ipsum</p>
  <footer class="blockquote-footer">Kyle Edward from<cite title="">Hogwarts</cite> </footer>
</blockquote>
```
<br>
<br>
<h3>REM CSS Unit</h3>
<p>REM is a relative unit that takes the font-size of the root-the top level HTML element(eg. 16px) and sets it as the multiplier. So if we set 1rem, the size will be 16px, if we set 2rems, the size will be 32px and so on.</p>
<p>It is important to keep in mind that if this root font-size changes all of our sizing will shift as well.</p>

<br>
<br>
<h2>⚡️New Spacing Utilities</h2>
<br>
<h3>Borders</h3>
<br>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-14-15-e1547624651876.png" width="400" height="160">

```javascript
<span class="border"></span>
<span class="border-top"></span>
<span class="border border-danger"></span>  // adding colourts

// Subtractive Border
<span class="border-0"></span>  // removes all borders
<span class="border-top-0"></span>

//Border Radius
<img src="" class="rounded">   // rounds all corners
<img src="" class="rounded-circle">  // circle radius
```
<img src="https://i.imgur.com/OXiRE.png" width="400" height="160">
<br>
<br>

<h3>Padding</h3>


```javascript
<button class="p-0">Button</button>  // sets padding of 0 all around
<button class="p-3">Button</button>  // sets padding of 3 all around
<button class="pt-5">Button</button>  // sets padding of 5 on top
<button class="py-5">Button</button>  // sets padding of 5 on top and bottom(y axis)
```
<br>
<img src="https://www.jquery-az.com/wp-content/uploads/2018/02/27-1-Bootstrap-padding.png" width="400" height="250">
<br>
<h3>Margin</h3>
<p>Same concept as padding</p>
<br>
<img src="https://www.jquery-az.com/wp-content/uploads/2018/02/27-3-Bootstrap-marging-all.png" width="400" height="250">
<br>
<br>

<h2>⚡️Responsive Breakpoints</h2>
<br>
<ul>
  <li>Extra Small - no 'xs' since this is the default</li>
  <li>Small - sm</li>
  <li>Medium - md</li>
  <li>Large - lg</li>
  <li>Extra Large - xl</li>
</ul>
<p>We can selectively add margin and padding depending on the screen-size (i.e maybe you want your components to be more spaced out in a large screen and no space in small screen, etc.)</p>

```html
<button class="p-sm-5 p-md-0">Button</button>  // from sm breakpoint we have p-5, from md breakpoint we have p-0
<button class="p-0 p-sm-2">Button</button>  // default is xs; we have p-0 at xs, we have p-2 at sm
```

<p>**Same concept with margin</p>  

<br>
<br>
<h2>⚡️Navbar</h2>
<br>

```html
 <nav class="navbar navbar-expand-lg navbar-light bg-light"> // makes our navbar, navbar items stack except lg
  <div class="container">  // makes sure all our items are in a center margin
    <a class="navbar-brand" href="#">Navbar</a>  // our main item
      <div class="navbar-collapse">  // everything in here will be our items
        <div class="navbar-nav">  // layouts our item properly
          <a class="nav-item nav-link" href="#">Home</a>  //item
          <a class="nav-item nav-link" href="#">About</a> //item
        </div>
      </div>
      <div class="navbar-nav">  //layouts our item properly; not inside navbar-collapse; it will stick to the left side
        <a class="nav-item nav-link" href="#">Sign In</a> //item
        <a class="nav-item nav-link" href="#">Sign Out</a>  //item
      </div>
  </div>
 </nav>
```

<br>
<br>

<img src="https://www.script-tutorials.com/wp-content/uploads/2015/01/navbar3-700x357.jpg" height=200px width=500px>

<br>

To implement actions/features include jquery cdn first and then the bootstrap javascript cdn because it relies on jquery. (This already done in <em>There are 2 ways to use Bootstrap</em>

```html
// including a hamburger
// hiding our items to a hamburger in mobile version

<nav class="navbar navbar-expand-lg navbar-dark" style="background-color: red;"> //NAVBAR; stacks except in lg; white text(navbar-dark)
  <div class="container"> // putting all our items in a container; has auto margin to center
    <a class="navbar-brand" href="#">Navbar</a> // MAIN ITEM
    // HAMBURGER ICON THAT TARGETS OUR ITEM TO COLLAPSE
    <button
      class="navbar-toggler"
      type="button
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="navbarSupportedContent"> // pur items; items collapsible to hamburger
      <ul class="navbar-nav mr-auto"> //layouts our items properly to stack to the left; our first set of items
        <li>
          <a class="nav-link" href="#">Home</a>  //ITEM
        </li>
        <li>
          <a class="nav-link" href="#">Link</a> //ITEM
        </li>
      </ul>
      <ul class="navbar-nav navbar-right"> //layouts our items to the right; our second set of items
        <li>
          <a class="nav-link" href="#">Sign In</a>  //ITEM
        </li>
        <li>
          <a class="nav-link" href="#">Sign Out</a> //ITEM
        </li>
      </ul>
    </div>
  </div>
</nav>
```

<br>
<br>

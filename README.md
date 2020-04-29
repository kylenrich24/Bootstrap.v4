# Bootstrap.v4
<img src="https://blog.templatetoaster.com/wp-content/uploads/2019/09/What-is-Bootstrap-Facebook.png" height="500" width="1000">
<p>Bootstrap is an HTML, CSS and JS framework for developing responsive, mobile-first projects on the web.</p>
<p>DOCS: https://getbootstrap.com/docs/4.3/components/alerts/</p>
<p>There are 2 ways to use Bootstrap:</p>
<ul>
<li>Download the files and it to your application</li>
  <ol>
    <li>Download the files https://getbootstrap.com/docs/4.3/getting-started/download/</li>
    <li>We need <em>bootstrap.css</em> or <em>bootstrap.min.css</em> from <em>/css/css/bootstrap.css</em></li>
    <li>Copy and paste this to the same directory where your app is in</li>
    <li>Link using a stylesheet link tag</li>
  </ol>
<li>Link CDN</li>
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

<h2>Differences from v3</h2>
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
<h2>Colors and Backgrounds</h2>
<p>Bootstrap takes advantage of Contextual Colours</p>
<br>
<h3>Bootstrap Colour List</h3>
<img src="https://bootstrap.themes.guide/assets/howto/colors.png" width="500px" height="180">

<h3>Text Colours</h3>
<img src="https://www.jquery-az.com/wp-content/uploads/2018/01/15-3-Bootstrap-link-colors.png" width="200px" height="180">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20190426131212/background_color_list.png" width="400px" height="180">

<br>
<br>

<h2>Typography</h2>
<p><strong>Display</strong> - acts like header tag, but are significantly bigger</p>
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
<p><strong>Blockquotes</strong></p>
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
<p><strong>REM CSS Unit</strong></p>
<p>REM is a relative unit that takes the font-size of the root-the top level HTML element(eg. 16px) and sets it as the multiplier. So if we set 1rem, the size will be 16px, if we set 2rems, the size will be 32px and so on.</p>
<p>It is important to keep in mind that if this root font-size changes all of our sizing will shift as well.</p>

<br>
<br>
<h2>New Spacing Utilities</h2>
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

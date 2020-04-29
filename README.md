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
<img src="https://bootstrap.themes.guide/assets/howto/colors.png" width="500px" height="180">

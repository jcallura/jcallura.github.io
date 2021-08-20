## WorldViewR
### Launch: <a href="http://44.230.157.126:3838" class="button">Server A</a> - <a href="http://54.68.18.107:3838" class="button">Server B</a>

<a href="https://github.com/jcallura/jcallura.github.io/blob/gh_pages/WorldViewR_demo.gif">Show Visual Demo</a><p>
This application provides a point and click interface that allows users to quickly render interactive 3D elevation models. 
Draw a bounding box on the map, click the button to download elevation data, then navigate to the second tab to render, view, and modify the resulting 3D site model. 
Hover over the 3D model to view point elevations, click and drag to rotate, or scroll to zoom in and out. Models and raw data can be exported in various file formats for use with external software. WorldViewR is currently optimized for desktop use and some features may be unavailable on mobile devices.
<p>
<!--<img src="https://github.com/jcallura/jcallura.github.io/blob/gh_pages/WorldViewR_demo.gif" width="400" height="400" />-->
    <!--#### THIS APPLICATION HAS BEEN TEMPORARILY DISABLED FOR MAINTENANCE-->
<!--<form action="http://44.230.157.126:3838">
    <input type="submit" value="Launch Web Application" />
</form>-->
<!--<a href="http://44.230.157.126:3838" class="button">Launch Web Application</a>
<br>-->

<h5>Usage and attribution</h5>
To cite this program, please use:
<p>
Jonathan C. Callura (2021). WorldViewR: Interactive elevation mapping and 3D modeling program. Accessed at <a href="https://jcallura.github.io">https://jcallura.github.io</a>
<br/>
<p>
WorldViewR was built with the R programming language using the Shiny package. Elevations represent bare-earth terrain heights from open source terrain tiles (<a href="https://registry.opendata.aws/terrain-tiles/" class="button">terrain tile source</a>; <a href="https://github.com/tilezen/joerd/blob/master/docs/attribution.md" class="button">data source attribution</a>). Street map tiles are provided by OpenStreetMap contributors (<a href="https://www.openstreetmap.org/copyright">data source attribution</a>).
<br/>

<h5>Support the project</h5>
This open access program is free for all to use. Please note that performance may vary depending on traffic volume. If you would like to help offset server and maintenance costs, click the PayPal donate button below.

<br/>
<form action="https://www.paypal.com/donate" method="post" target="_top">
<input type="hidden" name="business" value="9VBZZGE44GFSA" />
<input type="hidden" name="item_name" value="WorldViewR Maintenance Costs" />
<input type="hidden" name="currency_code" value="USD" />
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
<img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
</form>
 
<h5>Request new features, report a bug, or provide feedback</h5>

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mzbknapj" method="post">
    <fieldset id="fs-frm-inputs">
      <label for="full-name">Name</label>
        <br>
      <input type="text" name="name" id="full-name" placeholder="Optional">
        <br>
      <label for="email-address">Email Address</label>
        <br>
      <input type="email" name="_replyto" id="email-address" placeholder="Optional">
        <br>
      <label for="message">Message</label>
        <br>
      <textarea rows="5" name="message" id="message" placeholder="Message" required=""></textarea>
      <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
    </fieldset>
    <input type="submit" value="Submit">
  </form>

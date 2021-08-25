## WorldViewR
### Launch: <a href="http://44.230.157.126:3838" class="button">Server A</a> - <a href="http://54.68.18.107:3838" class="button">Server B</a>

<details style="margin-top:20px">
    <summary><strong>Instructions</strong></summary>
    
    <br/>
    <!--<img src="https://github.com/jcallura/jcallura.github.io/blob/gh_pages/WorldViewR_demo.gif?raw=true">-->
    <a href="https://github.com/jcallura/jcallura.github.io/blob/gh_pages/WorldViewR_demo.gif?raw=true">Show Visual Demo</a>
    <p>
    This application provides a point and click interface that allows users to quickly render interactive 3D elevation models. Draw a bounding box on the map, click the button to download elevation data, then navigate to the second tab to render, view, and modify the resulting 3D site model. Hover over the 3D model to view point elevations, click and drag to rotate, or scroll to zoom in and out. Models and raw data can be exported in various file formats for use with external software. WorldViewR is currently optimized for desktop use and some features may be unavailable on mobile devices.
    </p>
</details>

<details style="margin-top:20px">
    <summary><strong>Usage and Attribution</strong></summary>
    
    <br/>
    WorldViewR was built with the R programming language using the Shiny package. Elevations represent bare-earth terrain heights from open source terrain tiles (<a href="https://registry.opendata.aws/terrain-tiles/" class="button">terrain tile source</a>; <a href="https://github.com/tilezen/joerd/blob/master/docs/attribution.md" class="button">data source attribution</a>). Street map tiles are provided by OpenStreetMap contributors (<a href="https://www.openstreetmap.org/copyright">data source attribution</a>). To cite this program, please use:
    <p>
        Jonathan C. Callura (2021). WorldViewR: Interactive elevation mapping and 3D modeling program. Accessed at https://jcallura.github.io
    </p>
</details>   

<details style="margin-top:20px">
    <summary><strong>Support the Project</strong></summary>
        
    <br/>
        This open access program is free for all to use. Please note that performance may vary depending on traffic volume. If you would like to help offset server and maintenance costs, click the PayPal donate button below.
    <br/>
    <form action="https://www.paypal.com/donate" method="post" target="_top">
        <input type="hidden" name="business" value="9VBZZGE44GFSA" />
        <input type="hidden" name="item_name" value="WorldViewR Maintenance Costs" />
        <input type="hidden" name="currency_code" value="USD" />
        <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Donate with PayPal button" />
        <img alt="" border="0" src="https://www.paypal.com/en_US/i/scr/pixel.gif" width="1" height="1" />
    </form>
</details>

<details style="margin-top:20px">
    <summary><strong>Provide Feedback</strong></summary>
    
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
</details>

<h2 style="margin-top=60px">WorldViewR Pro</h2>
Support for higher resolution models, more capabilities, and active feature development. Coming soon...

<a href="https://docs.google.com/forms/d/e/1FAIpQLSfI9v8nce9wPsi3ywQYPBVtkLFvxyN5RKmTNPkN6kQ-mFu7oA/viewform?embedded=true">Click to join the waiting list for WorldViewR Pro</a>

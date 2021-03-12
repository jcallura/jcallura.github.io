### Map3D
This application provides a point and click interface that allows users to quickly render interactive 3D elevation models. Draw a bounding box on the map, click the button to download elevation data, then navigate to the second tab to render, view, and modify the resulting 3D site model. Hover over the 3D model to view point elevations, click and drag to rotate, or scroll to zoom in and out.
<br><br>
<!--#### THIS APPLICATION HAS BEEN TEMPORARILY DISABLED FOR MAINTENANCE-->
[Launch Web Application](http://44.230.157.126:3838)
<br><br>
#### Request new features, report a bug, or provide feedback
<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/mzbknapj" method="post">
    <fieldset id="fs-frm-inputs">
      <label for="full-name">Full Name</label>
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
  <script>
      $('.contact1-form').on('submit',function(e){
        //optional validation code here
  
        e.preventDefault();
      
        $.ajax({
            url: "https://script.google.com/macros/s/AKfycbxFKTaVyB0E-MraPA3ZAeNKpe1ikqq0MM2d1xFsreECdE1qjYJ84pXl5cbbXk0z6no/exec",
            method: "POST",
            dataType: "json",
            data: $(".contact1-form").serialize(),
            success: function(response) {
                
                if(response.result == "success") {
                    $('.contact1-form')[0].reset();
                    alert('Thank you for providing feedback.');
                    return true;
                }
                else {
                    alert("Something went wrong. Please try again.")
                }
            },
            error: function() {
                
                alert("Something went wrong. Please try again.")
            }
        })
    });
  </script>
  </form>

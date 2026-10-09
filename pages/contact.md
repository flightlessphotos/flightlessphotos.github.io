---
layout: page
title: Contact Me
permalink: /contact
---

<link rel="stylesheet" href="{{ site.github.url }}/assets/css/forms.css">
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/blocks.css">
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/imgboxrows.css">
<script>
window.onbeforeunload = () => {
  for(const form of document.getElementsByTagName('form')) {
    form.reset();
  }
}

// This does not work because we are using formspree.io
// Typically you would add onsubmit="formRedirect()" to the <form>
function formRedirect() {
  window.location.href = '/contact-thanks';
}
</script>

<div class="white-block">
<div class="row">
<div class="box">


<div class="contactform">
    <form id="contact" class="form autofill" method="POST" action="https://formspree.io/f/xqayezyj">
        <input type="hidden" name="subject" value="New submission!">    
        <div class="half">
            <label for="firstname">First name</label>
            <input type="text" name="firstname" id="firstname" class="form-control" required="">
        </div>
        <div class="half">
            <label for="lastname">Last name</label>
            <input type="text" name="lastname" id="lastname" class="form-control" required="">
        </div>
            
        <div>
            <label for="email">Email address (reply will be sent here!)</label>
            <input type="email" name="email" id="email" class="form-control" required="">
        </div>

         <div>
            <label for="message">Message</label>
            <textarea name="message" id="message" cols="30" rows="10" class="form-control" required=""></textarea>
        </div>
        
        <div>
            <input type="submit" value="Submit form" class="btn btn-primary">
        </div>

    </form>
</div>
</div> <!-- end box -->
<div class="box"><img src="{{ site.github.url }}/assets/img/contact/japan.jpg"/></div>
</div> <!-- end row -->
</div> <!-- end white-block -->


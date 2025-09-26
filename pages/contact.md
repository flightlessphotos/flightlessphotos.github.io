---
layout: page
title: Contact Us
permalink: /contact
---

<link rel="stylesheet" href="{{ site.github.url }}/assets/css/forms.css">
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/blocks.css">
<link rel="stylesheet" href="{{ site.github.url }}/assets/css/imgboxrows.css">

<div class="white-block">
I am honored and excited that you are interested in working with me!
Please fill out the information below and I will get in touch with you soon.

<p>You can also contact me directly </p>
<ul>
  <li>Email <a href="mailto:dan@flightlessphotos.com">dan@flightlessphotos.com</a></li>
  <li>Text or Call <a href="tel:3047294636">(304) 729-4636</a></li>
</ul>
</div> <!-- end white-block -->


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
            <label for="email">Email address</label>
            <input type="email" name="email" id="email" class="form-control" required="">
        </div>

        <div>
            <label for="email">Confirm Email address</label>
            <input type="confirmemail" name="confirmemail" id="confirmemail" class="form-control" required="">
        </div>

         <div>
            <label for="phone">Phone</label>
            <input type="phone" name="phone" id="phone" class="form-control" required="">
        </div>

       
        <div> Preferred Contact Method </div>
        <div class="radio">
            <label><input type="radio" name="contactmethod" value="Phone" required="">Phone</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="contactmethod" value="Email" required="">Email</label>
        </div>
         <div class="radio">
            <label><input type="radio" name="contactmethod" value="Text" required="">Text</label>
        </div>
        
        <div> Preferred Contact Time </div>
        <div class="radio">
            <label><input type="radio" name="contacttime" value="mornings" required="">Mornings (9am - Noon)</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="contacttime" value="afternoons" required="">Afternoons (Noon - 5pm)</label>
        </div>
         <div class="radio">
            <label><input type="radio" name="contacttime" value="evenings" required="">Evenings (5pm - 8pm)</label>
        </div>
 

        <div> Photoshoot Type </div>
        <div class="radio">
            <label><input type="radio" name="session" value="cosplay" required="">Cosplay Portraits</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="session" value="kids-personality" required="">Kids Personality Portraits</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="session" value="maternity" required="">Maternity Portraits</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="session" value="sports" required="">Sports Portraits</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="session" value="pets" required="">Pet Portraits</label>
        </div>
        <div class="radio">
            <label><input type="radio" name="session" value="event" required="">Event Photography</label>
        </div>
         <div class="radio">
            <label><input type="radio" name="session" value="other" required="">Something else!</label>
        </div>
 

         <div>
            <label for="message">Message (optional)</label>
            <textarea name="message" id="message" cols="30" rows="10" class="form-control"></textarea>
        </div>
        
        <!--
        <div class="checkbox">
            <label><input type="checkbox" name="terms" value="I would accept the terms and conditions (if there were any)" required="">I would accept the terms and conditions (if there were any)</label>
        </div>
        -->
        
        
        <div>
            <input type="submit" value="Submit form" class="btn btn-primary">
        </div>

    </form>
</div>
</div> <!-- end box -->
<div class="box"><img src="{{ site.github.url }}/assets/img/japan.jpg"/></div>
</div> <!-- end row -->
</div> <!-- end white-block -->


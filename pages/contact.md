---
layout: page
title: Contact Me
permalink: /contact
---
<style>

/* FORMS */

.contactform{
    max-width: 36rem;
    background-color: #f8f8f8;
}
form {max-width: 34rem;
    margin-top: 20px;
    margin-right: 20px;
    margin-bottom: 20px;
    margin-left: 20px;
}
form > div {padding-top: 0.8rem; clear: both;}
form > div.half {width: 47.5%; float: left;}
form > div.half + .half {margin-left: 5%; clear: none;}
label {display: block; margin-bottom: 0.3rem;}
textarea, input, select {
    font-family: 'Open Sans'; 
    font-size: 0.8rem; 
    height: 1.83rem; 
    line-height: 1rem; 
    border: 0.0625rem solid #dddddd; 
    border-radius: 0.25rem;
    width: calc(100% - 1.24rem);
    padding: 0.1875rem 0.625rem;
    background: white;
    color: #777777;
}
select {padding: 0.6rem; height: auto; line-height: 1.4; width: 100%;}
textarea {height: auto; line-height: 1.4; min-width: calc(100% - 1.24rem); max-width: calc(100% - 1.24rem); padding: 0.6rem;}
input[type="button"], input[type="submit"], input[type="radio"], input[type="checkbox"] {border: 0; width: auto;}
input[type="radio"], input[type="checkbox"] {height: auto; line-height: auto; margin-right: 0.4rem; vertical-align: middle; position: relative; bottom: 0.1rem;}
.radio {position: relative; top: 0.125rem;}
.radio + .radio {padding-top: 0;}
input[type='number'] {-moz-appearance: textfield;}
input::-webkit-outer-spin-button, input::-webkit-inner-spin-button {-webkit-appearance: none;}
.btn, input[type="submit"] {
    background: #000000; /*#d9230f; */
    font-weight: bold; 
    color: rgba(255,255,255,0.75); 
    text-decoration: none;
    padding: 0.35rem 0.7rem;
    border: 0;
    cursor: pointer;
    border-radius: 0.25rem;
}
.btn:hover {color: rgba(255,255,255,0.9);}
input[type="number"] {-moz-appearance: textfield;}
input[type="number"].quantity {width: 1.5rem; min-width: 1.5rem; text-align: center;}
input::-webkit-outer-spin-button, 
input::-webkit-inner-spin-button {-webkit-appearance: none;}
select::-ms-expand {display: none;}
select {
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    background: white url("/img/chevron_down.svg") calc(100% - 0.8rem) 55% no-repeat;
    background-size: auto 0.7rem;
}
</style>

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

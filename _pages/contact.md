---
permalink: /contact/

title: Contact
---

<div class="pt-12"></div>

<script type='text/javascript'
    src='https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js'>
</script>

<h2 class="text-center"> Contact Me </h2>

<style>
    form > .grid > *
    {
        display: inline;
    }
</style>

<form name='sentMessage' onsubmit='return false' id='contactForm' novalidate='novalidate' class="grid row-gap-10" style="max-width: 20rem;">
    <div class="flex flex-column">
        <label><i class='fas fa-user-circle'></i> Name </label>
        <input
            id='name'
            type='text'
            placeholder='Name'
            required='required'
            data-validation-required-message='Please enter your name'
        />
    </div>
    <div class="flex flex-column">
        <label><i class='fas fa-at'></i> Email Address </label>
        <input
            class='form-control'
            name="email"
            id='email'
            type='email'
            placeholder='Email Address'
            required='required'
            data-validation-required-message='Please enter your email address'
        />
    </div>
    <div class="flex flex-column">
        <label><i class='fas fa-phone-alt'></i> Other form of contact </label>
        <input
            class='form-control'
            id='phone'
            type='text'
            placeholder='Phone Number'
            required='required'
            data-validation-required-message='Please enter your phone number'
        />
    </div>
    <div class="flex flex-column">
        <label><i class='fas fa-envelope-open-text'></i> Message </label>
        <textarea
            class='form-control'
            id='message'
            rows='5'
            placeholder='Message'
            required='required'
            data-validation-required-message='Please enter a message'
        ></textarea>
    </div>
    <div id='success'></div>
    <button class="mx-auto" id='submit' type='submit' value='submit' onclick='sendMail()'>
        Submit
    </button>
    <div class="flex flex-column items-center">
        <h3> Feel free to email at </h3>
        <a href="/email"> TrystonMinsquero@gmail.com</a>
    </div>
</form>

<div class="pt-12"></div>
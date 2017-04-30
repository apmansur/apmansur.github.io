---
layout: page
title: Contact
permalink: /contact/
feature-img: "img/color.png"
---

Thank you for your interest in my work! Feel free to use the form below to ask me any questions you may have or if you are interested in working together to develop awesome ideas!


<form action="php/send_email.php" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='https://github.com/apmansur' >
  <input type='text' name='name' placeholder='Your Full Name' />
  <input type='email' name='email' placeholder='Your E-mail Address' />
  <textarea name='message' placeholder='Write your message ...'></textarea>
  <input type='submit' value='Send Message' />
</form>

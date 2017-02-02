---
layout: page
title: Contact
desc: I would like to hear suggestions from you.
permalink: /contact/
---

This is a sample form. Update API TOKEN recieved from [SimpleForm](https://getsimpleform.com){: target="_blank" rel="nofollow"} in the _config.yml

<form action="https://getsimpleform.com/messages?form_api_token=<form_api_token>" method="post">

  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='<the complete return url e.g. http://fooey.com/thank-you.html>' />

  <!-- all your input fields here.... -->
  <input type='text' name='test' />

  <input type='submit' value='Test form' />
</form>



<style>
.contact-li {
    list-style: none;
}

.contact-input {
    border:none;
    border-bottom: 1px solid #eee;
    transition-duration: 0.3s;
    width: 12em;
}

.contact-input:focus {
    outline:none;
    border-bottom: 1px solid {{site.accent-color}};
}

.contact-label {
    display: block;
}

ul.contact-ul {
    margin: 0;
    padding: 10px;
}

#submit {
    border:none;
    background-color: {{site.accent-color}};
    padding: 5px 15px;
    color: #eee;
    opacity: 0.8;
}

#submit:hover {
    opacity: 1;
    cursor: pointer;
}


#contact-form {
    border: 1px solid #aaa;
    display: inline-flex;
    margin-bottom: 1em;
}

</style>
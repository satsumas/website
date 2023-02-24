---
title: Contact
subtitle: Get in touch
description: Duet is a beautiful Jekyll portfolio theme.
featured_image: /images/demo/demo-landscape.jpg
---

{% include contact-form.html %}

We've made a contact form that you can use with [Formspree](https://formspree.io/create/jekyllthemes) to handle up to 50 submissions per month for free. You could also easily switch out the end-point to use another contact form service.

<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xeqwgwpw"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
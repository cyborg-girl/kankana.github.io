---
layout: single
title: "Contact"
author_profile: false
---

<form action="https://formspree.io/f/your-form-id" method="POST">
  <label>Your email
    <input type="email" name="email" required>
  </label>
  <label>Your message
    <textarea name="message" rows="6" required></textarea>
  </label>
  <!-- honeypot -->
  <input type="text" name="_gotcha" style="display:none">
  <button type="submit">Send</button>
</form>

_Tip: replace `your-form-id` with your Formspree endpoint._

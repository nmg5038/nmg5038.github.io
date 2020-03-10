---
layout: page
title: Contact Me
permalink: /Contact Me/
---

Please use this contact form to send me a message!  You will also find my resume
and CV to download.

<table style="width:50%; float: right">
<tr>
  <th>Professional Downloadables</th>
</tr>
<tr>
  <td>
    <a href="{{ site.url }}/resume/ng_resume_2020.pdf">Resume</a>
    (Jan 2020)
  </td>
</tr>
<tr>
  <td>
  <a href="{{ site.url }}/resume/geyer-cv.pdf">Curriculum Vitae</a>
  (Jan 2020)
  </td>
</tr>
</table>

  <form name="input" accept-charset="utf-8" method="POST" action="https://formspree.io/nmg5038@gmail.com" style="width:50%">
  <fieldset>
  <label for="full-name">Name<br /></label>
  <input type="text" name="name" id="full-name" placeholder="First and Last" required=""><br />
  <label for="email-address">Email Address<br /></label>
  <input type="email" name="_replyto" id="email-address" placeholder="your email addr" required=""><br />
  <label for="message">Message<br /></label>
      <textarea rows="5" name="message" id="message" placeholder="Fill this section out with your message to me!" required=""></textarea>
  </fieldset>
  <input type="submit" value = "Send"/>
  <input type="hidden" name="_subject" value="Contact Form Submission From Website"/>
  <input type="hidden" name="_gotcha"/>
  <input type="hidden" name="_next" value="index.markdown"/>
  </form>

---
layout: layout.html
---

# This Is A Content Page.

<form name="contact" method="POST" action="https://formsubmit.co/jacksonchao767@gmail.com" enctype="multipart/form-data">
  <p>
    <label>
      姓名：
      <input type="text" name="name" />
    </label>
  </p>
  <p>
    <label>
      電郵：
      <input type="email" name="email" />
    </label>
  </p>
  <p>
    <label>
      查詢內容：
      <textarea name="message"></textarea>
    </label>
  </p>
  <p>
    <label>
      Attachment:
      <input type="file" name="attachment">
    </label>
  </p>
  <p>
    <input type="hidden" name="_next" value="https://demo-20200516.netlify.app/thanks">
    <input type="submit" value="Send">
  </p>
</form>

---
date: '2026-07-26T18:13:46-07:00'
draft: false
title: 'About'
---

I am Liong! I like drawing cats, making art, and creating things. I've been having a lot of fun learning about electric machines, high voltage, and generally very glowy things. I made this website in case anyone wants to take a look at the stuff i've done. I'm also just posting anything cool i find here. 

![Selfie](image.jpg)



<button id="open-tabs-btn" style="padding: 10px 20px; border-radius: 8px; border: 1px solid var(--border); background: var(--entry); cursor: pointer; font-size: 0.95rem;">
  Click me >:D
</button>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const btn = document.getElementById("open-tabs-btn");
  if (btn) {
    btn.addEventListener("click", function () {
      for (let i = 0; i < 5; i++) {
        window.open("/cat/", "_blank");
      }
    });
  }
});
</script>
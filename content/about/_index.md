---
date: '2026-07-26T18:13:46-07:00'
draft: false
title: 'About'
---

## HELLO

Your existing about page content here...

<button id="open-tabs-btn" style="padding: 10px 20px; border-radius: 8px; border: 1px solid var(--border); background: var(--entry); cursor: pointer; font-size: 0.95rem;">
  Open dummy sites
</button>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const btn = document.getElementById("open-tabs-btn");
  if (btn) {
    btn.addEventListener("click", function () {
      const urls = [
        "https://example.com",
        "https://www.wikipedia.org",
        "https://httpbin.org"
      ];
      urls.forEach(url => window.open(url, "_blank"));
    });
  }
});
</script>
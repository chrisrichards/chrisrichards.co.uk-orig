---
title: Home
date: 2018-06-05 20:37:00 Z
---

Just testing out Siteleaf CMS!

<script src="https://unpkg.com/vue"></script>

<div id="app">
  <p>{{ message }}</p>
</div>

<script>
  new Vue({
    el: '#app',
    data: {
      message: 'Hello Vue.js!'
    }
  })
</script>

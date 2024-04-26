---
title: Hello World
description: Welcome to my website
slug: hello-world
date: 2022-03-06 00:00:00+0000
image: cover.jpg
categories:
  - Example Category
tags:
  - Example Tag
weight: 1 # You can add weight to some posts to override the default sorting (date descending)
---

Welcome to Hugo theme Stack. This is your first post. Edit or delete it, then start writing!

For more information about this theme, check the documentation: https://stack.jimmycai.com/

Want a site like this? Check out [hugo-theme-stack-stater](https://github.com/CaiJimmy/hugo-theme-stack-starter)

> Photo by [Pawel Czerwinski](https://unsplash.com/@pawel_czerwinski) on [Unsplash](https://unsplash.com/)

<div id="browserAgent">Loading browser agent information...</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
  // Function to fetch User-Agent from the Cloudflare Worker
  function fetchUserAgent() {
    fetch('https://browser.rene-hu.workers.dev/')
      .then(function(response) {
        return response.text();
      })
      .then(function(data) {
        document.getElementById('browserAgent').textContent = data;
      })
      .catch(function(error) {
        console.error('Error fetching the User-Agent:', error);
        document.getElementById('browserAgent').textContent = 'Failed to load browser agent information.';
      });
  }

  // Call the fetchUserAgent function when the document is ready
  fetchUserAgent();
});
</script>

---
layout: default
title: Search
permalink: /search/
nav_exclude: true
---

# Search

Use the search box in the sidebar to find content on this site. The search looks through the homepage and all hadith pages for matching content.

<div id="search-info" style="margin-top: 20px;">
  <p><em>Start typing to search...</em></p>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const searchInput = document.getElementById('search-input');
    if (searchInput) {
      searchInput.focus();
    }
  });
</script>

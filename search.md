---
layout: default
title: Search
permalink: /search/
---

# Search

Use the search box above to find content on this site. The search will look through all hadith and pages for matching content.

<div id="search-info" style="margin-top: 20px;">
  <p><em>Start typing to search...</em></p>
</div>

<script>
  // Focus search input when on search page
  document.addEventListener('DOMContentLoaded', function() {
    const searchInput = document.getElementById('search-input');
    if (searchInput) {
      searchInput.focus();
    }
  });
</script>

---
layout: page
title: Search
permalink: /search/
---
<style>
.sbox {
    top: 20%;
    height: 100%;
    width: 90%;
    box-sizing: border-box;
    min-height: 40px;
    max-height: 52px;
    min-width: 100px;
    max-width: 596px;
    white-space: nowrap;
    z-index: 2;
    margin: 0px 0px 0px 0px;
}

.sboxdiv{
  margin: 0px 0px 0px 0px;
}

.rboxdiv {
  margin: 0px 0px 0px 0px;
  padding: 20px 0px 0px 0px;
}
</style>

<!-- Html Elements for Search -->
<div class="sboxdiv" id="search-container">
<input class="sbox" type="text" id="search-input" placeholder="search...">
</div>
<div class="rboxdiv">
<ul id="results-container"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json'
})
</script>
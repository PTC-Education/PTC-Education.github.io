---
layout: doc
title: Search Results
permalink: /search
---
<section class="section">
    <div id="search-input-container">
      Search DX in Education: <input type="search" id="search-input" placeholder="">
      <br /><br />
    </div>
    <div id="search-results-container">
      <ul id="results-container"></ul>
    </div>
</section>
<script src="{{ site.baseurl }}/js/simple-jekyll-search.min.js"></script>
<script>
function GetQueryString(name)
{
     var reg = new RegExp("(^|&)"+ name +"=([^&]*)(&|$)");
     var r = window.location.search.substr(1).match(reg);
     if(r!=null)return  unescape(r[2]); return null;
}
var mykeyword = GetQueryString("keyword");
var sbox = document.getElementById('search-input');
var status = false;
if(mykeyword !=null && mykeyword.toString().length>1){
     sbox.value = mykeyword;
}
var sjs = SimpleJekyllSearch({
     searchInput: sbox,
     resultsContainer: document.getElementById('results-container'),
     json: '{{ site.baseurl }}/search.json',
     searchResultTemplate: '<li><br /><a href="{{ site.url }}{url}">{title}</a><br />{description}<br /><br /></li>',
});
$(window).bind("load", function () {
     sjs.search(mykeyword);
})
</script>



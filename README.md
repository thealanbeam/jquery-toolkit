# jQuery toolkit

## Append class to External Links
<pre><code>
$('a[href^="http"]').attr('class', 'external-link');
</code></pre>


## Applying link to entire div
When you have a div you want to act as a large button?

<pre><code>
//Searches for div with buttondiv class and makes entire div clickable as a link.
$(".buttondiv").click(function(){
     window.location=$(this).find("a").attr("href"); 
     return false;
});
</code></pre>


## Scroll to top of page
<pre><code>
// Without animation
$( document.body ).scrollTop( 500 );

// With animation
$( document.body ).animate({
  scrollTop: 500
});
</code></pre>


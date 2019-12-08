<b><span style='font-size:4em'>Gradient Dark Theme</em></b>

Syntax highlighting


<link rel="stylesheet" href="gradient-dark.css">
<script src="highlight.pack.js"></script>
<script>hljs.initHighlightingOnLoad();</script>



<pre><code>
  /*css code*/ 
@font-face {
  font-family: Chunkfive; src: url('Chunkfive.otf');
}

body, .usertext {
  color: #F0F0F0; background: #600;
  font-family: Chunkfive, sans;
  --heading-1: 30px/32px Helvetica, sans-serif;
}

@import url(print.css);
@media print {
  a[href^=http]::after {
    content: attr(href)
  }
}
Diff
</code></pre>

<pre><code>
/*Javascript code*/
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }
return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}
export  $initHighlight;
</code></pre>

<pre><code>
 /*R Markdown*/ 
plot <- function (x, y, ...)
{
  if (is.function(x) && 
      is.null(attr(x, "class")))
  {
    if (missing(y))
      y <- NULL
    
    # check for ylab argument
    hasylab <- function(...) 
      !all(is.na(
        pmatch(names(list(...)),
              "ylab")))
    
    if (hasylab(...))
      plot.function(x, y, ...)
    
    else 
      plot.function(
        x, y, 
        ylab = paste(
          deparse(substitute(x)),
          "(x)"), 
        ...)
  }
  else 
    UseMethod("plot")
</code></pre>

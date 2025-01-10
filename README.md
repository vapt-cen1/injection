# injection

pentest

<script>alert('XSS');</script>

![Broken Image](invalid.jpg ':size=250' )
<img src="invalid.jpg" onerror="alert('XSS')">

<svg onload="alert('XSS')"></svg>

<img src="valid-image.jpg" alt="test" title="XSS" onerror=alert('XSS')>

<img src="valid-image.jpg" alt="test" title="><script>alert('XSS')</script>">

<iframe src="javascript:alert('XSS');"></iframe>

[Click Me](javascript:alert('XSS'))

[malicious link](something"onmouseover="alert('XSS'))



## iFrames Test

<figure>
<iframe width="425" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://i.ytimg.com/vi/-IXqbuMOwYg/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDmcWpHub9FsBmp6vQgQTz0sWK14Q" style="border: 1px solid black"></iframe>
</figure>

<figure>
<iframe width="560" height="315" src="https://www.youtube.com/embed/-IXqbuMOwYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</figure>

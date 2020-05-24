---
title: Facebook
layout: default
---

## Div approach

This is a required section:

```html
<!-- Container for iframe which will be inserted by JS. -->
<div id="fb-root"></div>

<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v4.0">
</script>
```

<!-- Container for iframe which will be inserted by JS. -->
<div id="fb-root"></div>

<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v4.0">
</script>


### Timeline and events for Facebook's own page

<!-- Widget -->
<div class="fb-page" data-href="https://www.facebook.com/facebook" data-tabs="timeline,events" data-width=""
    data-height="" data-small-header="true" data-adapt-container-width="true" data-hide-cover="false"
    data-show-facepile="false">
    <blockquote cite="https://www.facebook.com/facebook" class="fb-xfbml-parse-ignore"><a
            href="https://www.facebook.com/facebook">Facebook</a></blockquote>
</div>


### Events for Second Liners Improv page

<!-- Widget -->
<div class="fb-page" data-href="https://www.facebook.com/secondlinersimprov" data-tabs="events" data-width=""
    data-height="" data-small-header="true" data-adapt-container-width="true" data-hide-cover="false"
    data-show-facepile="false">
    <blockquote cite="https://www.facebook.com/secondlinersimprov" class="fb-xfbml-parse-ignore"><a
            href="https://www.facebook.com/secondlinersimprov">The Second Liners Improv Troupe</a></blockquote>
</div>


## Iframe approach

Note that is a standalone a approach which does _not_ need the `fb-root` element and script tag in the first approach.

```html
<iframe
    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fsecondlinersimprov&tabs=events&width=340&height=200&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=false&appId"
    width="340" height="200"
    style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"
    allow="encrypted-media">
</iframe>
```


<iframe
    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fsecondlinersimprov&tabs=events&width=340&height=200&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=false&appId"
    width="340" height="200"
    style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true"
    allow="encrypted-media">
</iframe>

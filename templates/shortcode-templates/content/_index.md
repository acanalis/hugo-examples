---
title: My Website
---

# ~ My Website ~

## Single-word Example: `year`

The year is {{< year >}}.

## Single Positional Example: `youtube`

{{< youtube 09jf3ow9jfw >}}

## Single Named Example: `image`

{{< img src="/media/smiley.png" title="Smiley" >}}

## Single Flexible Example: `vimeo`

{{< vimeo 49718712 >}}

{{< vimeo id="49718712" class="flex-video" >}}

### Paired Example: `highlight`

{{< myhighlight html >}}
<html>
<body> This HTML </body>
</html>
{{< /myhighlight >}}

## Nested Shortcode: Image Gallery

{{< gallery class="content-gallery" >}}
  {{< img2 src="/media/one.png" >}}
  {{< img2 src="/media/two.png" >}}
{{< /gallery >}}
{{< img2 src="/media/three.png" >}}

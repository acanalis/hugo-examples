# absURL

[Original Hugo Docs Article](https://gohugo.io/functions/absurl/)

To follow this example:
1. Read `layouts/_default/list.html`.
2. Run `hugo` on this folder.
3. Read `public/index.html`.

## Differences to the Docs version

The example was slightly edited to match the function signature. 

The original was `{{ "mystyle.css" | absURL }}` , but it was changed to `{{ absURL "mystyle.css" }}`.
# absLangURL
[Original Hugo Docs Article](https://gohugo.io/functions/abslangurl/)

To follow this example:
1. Read `layouts/_default/list.html`.
2. Run `hugo` on this folder.
3. Read `public/en/blog/index.html`.

## Differences to the Docs version

The example was slightly edited to match the function signature. 

The original was `{{ "blog/" | absLangURL }}` , but it was changed to `{{ absLangURL "blog/"}}`.
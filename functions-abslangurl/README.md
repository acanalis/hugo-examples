# absLangURL
[Original Docs Article](https://gohugo.io/functions/abslangurl/)

To follow this example:
1. Run `hugo` on this folder.
2. View `layouts/list.html`.
3. View `public/en/blog/index.html`.

## Differences to the Docs version

The example was slightly edited to match the function signature. 

The original was `{{ "blog/" | absLangURL }}` , but it was changed to `{{ absLangURL "blog/"}}`.
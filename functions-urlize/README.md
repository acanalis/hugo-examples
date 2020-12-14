# urlize

[Original Docs Article](https://gohugo.io/functions/urlize/)

To follow this example:
1. Run `hugo` on this folder.
2. View `layouts/list.html`.
3. View `public/blog/index.html`.

## Differences to the Docs version

The example was slightly edited to match the function signature. 

The original was `{{ . | urlize }}` , but it was changed to `{{ urlize . }}`.

# Notes

* The examples shows a relatively bad practice of url-building by joining the different parts. There might be better alternatives.
* This examples adds the complexity of a taxonomy.
* This function is very simmilar to `anchorize`, so it should be linked in the "See Also".
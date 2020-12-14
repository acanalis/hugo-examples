# shortcode-templates

[Original Hugo Docs Article](https://gohugo.io/templates/shortcode-templates/)

To follow this example:
1. View `content/_index.md`
2. View the shortcode definitions at `layouts/shorcodes/`
3. Run `hugo`.
4. View `public/index.html`

## Differences to the Docs version

* All the examples were put into one content file for convenience. 
* The `highlight` shortcode was changed to `myhighlight` because it conflicted with Hugo's builtin one. 
* In Nested Shortcode, it `img` was changed to `img2`, to avoid conflict with the previous "Single Named Example: `image`"
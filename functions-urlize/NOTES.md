# urlize

[Original Hugo Docs Article](https://gohugo.io/functions/urlize/)

## Differences to the Docs version

* The original was `{{ . | urlize }}` , but it was changed to `{{ urlize . }}` to match the function signature.
* The taxonomy link was altered from `<a href="/locations/{{ urlize . }}">` to `<a href="/location/{{ urlize . }}">` to keep the config simple.

# Notes

* Url-building. The taxonomies URLs are built by joining strings. If the taxonomies are rendered on a different part of the site via the "permalink" config option, the links will break. Right now, there's no better option.
* This examples adds the complexity of a taxonomy.
* The function should be explicitly passed string arguments, without using the dot.
* This function is very simmilar to `anchorize`, so it should be linked in the "See Also".
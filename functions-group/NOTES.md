# group

[Original Hugo Docs Article](https://gohugo.io/functions/group/)

## Differences with the Docs version

Reduced the numbers to avoid generating so many content files.

## Notes

* Could avoid use of partial.
* What is the use case for group? The example shows a manual grouping, which isn't exactly useful. Wouldn't this be better? 
    ```go-templates-text
    {{ range $tag,$group := (groupBy .Pages ".Params.tags") }}   
    <h2> Tag: {{$tag}} </h2>
    {{ partial "listgroup.html" $group }}
    {{ end }}
    ```
    Of course, taxonomies have their own way to do this, but this might be convenient for other cases.
# after

[Original Hugo Docs Article](https://gohugo.io/functions/after/)

## Notes

* The second example is very interesting, but could be in a different place of the Docs.
* The suggested folder structure is awkward. The easiest idea to undestand is "folder structure of content = of layouts = output". The use of "section" breaks that logic. 
Suggested structure: 
    ```
    layouts
     └───index.html
     └───articles
          └───baseof.html
          └───single.html
          └───list.html
    ```
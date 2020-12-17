# ge

[Original Hugo Docs Article](https://gohugo.io/functions/ge)

## Diferences to the Docs version

* Simplified `{{ if ge 10 5 }}true{{ end }}` to `{{ ge 10 5 }}`.
* Added comparisons between strings and numbers. 

## Notes

* Same issues as in eq. The comparison operators should be all in one example, otherwise is too granular. 
* It seems that comparison between strings is [lexicographical](https://en.wikipedia.org/wiki/Lexicographic_order), but I'd need to look at the source.
* The following behaviour is undocumented: 
  
   ```go-templates-go
    {{ ge "10" 5 }}
    {{ ge "5" 10 }}
    ```

    I think that pure numbers are considered superior to strings.
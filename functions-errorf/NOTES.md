# errorf

[Original Hugo Docs Article](https://gohugo.io/functions/errorf)

This is the only example in the repository that doesn't build. It does so on purpose, with an error: 

```console
Start building sites …
ERROR 2020/12/16 13:35:04 Custom Error: Failed to handle page "_index.md"
Total in 105 ms
Error: Error building site: logged 1 error(s)
```

If the first line here is changed to ` {{if false}} ` (at `layouts/index.html`), the example builds perfectly

```go-templates-text
{{ if true }}
{{ errorf "Custom Error: Failed to handle page %q" .Path }}
{{ end }}
```

## Differences to the Docs version
* Added light context

## Notes
# warnf

[Original Hugo Docs Article](https://gohugo.io/functions/errorf)

Many examples print warnings (see `../README.md`) but this is the only case which does so on purpose, with warning: 

```console
Start building sites … 
WARN 2020/12/16 13:46:46 Custom Warning: Remember to set the title at the front matter of page "_index.md"
```

If the first line here is changed to ` {{if false}} ` (at `layouts/index.html`), the example builds perfectly

```go-templates-text
{{ if true }}
{{ warnf "Custom Warning: Remember to set the title at the front matter of page %q" .Path }}
{{ end }}
```

## Differences to the Docs version
* Added light context

## Notes
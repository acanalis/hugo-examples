# base64Encode & base64Decode

[Original Hugo Docs Article](https://gohugo.io/functions/base64/)

## Differences to the Docs version

* The original was `{{ "Hello World" | base64 }}` , but it was changed to `{{ base64 "Hello World" }}` to match the function signature.
* Quotes were added
* The "=" sign was changed to "->" to better represent conversion.
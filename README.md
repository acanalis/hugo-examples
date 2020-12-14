# hugo-examples

[ Note: Under Construction ]

A repository of Hugo examples as shown in the Hugo Docs, so that you can run them yourself. Not maintained by the Hugo Team.

## Get Started 

1. [Install Hugo](https://gohugo.io/getting-started/installing/)
2. Clone or download this repository.
3. Open your preferred terminal and navigate to one of the examples folder.
4. Run `hugo` (or `hugo server`).

Here's an example (requires git): 

```console
echo "checking git"
git version 
echo "checking hugo"
hugo version
git clone https://github.com/acanalis/hugo-examples
cd hugo-examples
cd functions-anchorize
hugo
```

## Notes

* The top level folders are valid Hugo folders (you can run `hugo` or `hugo server` in them).
* The aim is to implement all the examples from [this folder](https://github.com/gohugoio/hugoDocs/tree/master/content/en) of the Hugo Docs.
* The implementation is as true as possible to the original, except inconsistencies or bugs.

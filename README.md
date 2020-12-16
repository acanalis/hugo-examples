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
* The implementation is as true as possible to the original.
* The implementation is as minimal as possible.
* For consistency all the configurations and front matter parameter were converted to `.yaml`.  
* To keep the examples minimal, this warning is considered acceptable:
    > WARN 2020/12/15 20:21:41 found no layout file for "HTML" for kind "taxonomy": You should create a template file which matches Hugo Layouts Lookup Rules for this combination.
    
    To solve it, add a `layouts/_default/list.html`. 


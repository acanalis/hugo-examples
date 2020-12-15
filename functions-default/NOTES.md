# default

[Original Hugo Docs Article](https://gohugo.io/functions/default/)

## Differences to the Docs version

* The verbose examples that show why to use `default` weren't included
* Only one file (`content/_index.md`) was used for all the examples.

## Notes 

The explanation is vague, because it uses the word "checks". It should be changed to 
> default **returns** the first argument if the second argument is not set. 
> Not set means that the value is either:  
> * a zero valued numeric types or time.
> * a zero length string, array, map or slice.
> * a nil value of any type.
> 
> Structs and booleans are always considered as "set".

The example is needlessly long. One short example + One advanced example should be fine.

# .AddDate

[Original Docs Article](https://gohugo.io/functions/adddate/)

To follow this example:
1. Run `hugo` on this folder.
2. View `data/tweets.toml`
3. View `layouts/random-tweets.html`.
4. View `public/index.html`.

## Differences to the Docs version

The original version didn't work, because the "date" field on each tweet is a string, and `now` is of type time.Time. That mismatch cause all the tweets to be missed. To solve it, `now.AddDate -2 0 0` was formated into a string before the comparison.

Original was 
```
{{ range where $.Site.Data.tweets.tweet "date" "ge" (now.AddDate -2 0 0) | shuffle }}
```
and the current one is 
```
{{ range where $.Site.Data.tweets.tweet "date" "ge" ((now.AddDate -2 0 0).Format "2006-01-02") | shuffle }}
```

## Notes

This example shows too many functionalities at once, when at this place of the documentation it should be minimal. However, this example could prove valuable on a series of tutorials called "Mastering `where`" or similar.

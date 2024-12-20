t# Google / DDG Image Search - Firefox Search Shortcut
Useful firefox search shortcut that lets you use the searchbar to search google images

Instead of typing images.google.com or images.duckduckgo.com, then searching, or searching on google then clicking images, just open the adress/search bar, type ii [search_term]

---

## Instructions:

- Go to the adress bar and type `about:config`
- Search `browser.urlbar.update2.engineAliasRefresh` click add / plus (__+__) to add a new Boolean preference (set it to true)
- Go to the search shortcuts in settings or put `about:preferences#search` in the adress bar
- Click the __Add__ in the bottom right corner to make a new shortcut
- Search engine name: Put anything (ex. Google Image Search)

__Important__

- Engine URL:
  - For Google Images

    `https://www.google.com/search?tbm=isch&q=%s`
  - For DuckDuckGo Images

    `https://duckduckgo.com/?t=ffab&q=%s&iax=images&ia=images`
- Alias: Put a keyword so when you type it in the search bar your shortcut comes up automatically (Ex. gi or ii or di)

### Done!

---
Inspired by the reverse google image search shortcut by u/fsau on [reddit](https://www.reddit.com/r/firefox/comments/1d9miq2/comment/l7eod6o/)

## What is it?
Markdown Styler shows a styled markdown document form a URL of your choice.

## How do i use it?
Say you have a markdown document at `https://my.site/my/url.md`.
Just append the URL you want to style as parameter to this page like this:
```
	https://matteobrusa.github.io/md-styler/?url=https://my.site/my/url.md
```

## How does it work?
Markdown styler is a simple ajax hack standing on the shoulders of giants: [Strapdown.js](http://strapdownjs.com/) and [cors-anywhere](cors-anywhere.herokuapp.com).

Fork it [on Github](https://github.com/matteobrusa/md-styler).

## Can I use it with Dropbox links?
Sure! Markdown styler knows how to work with links from Dropbox.

## Can I use a different theme?
Sure, try adding a `theme=xyz` parameter with value `journal|simplex|bootstrap|superhero|slate|united`.

## Demo please
https://matteobrusa.github.io/md-styler/?url=https://matteobrusa.github.io/md-styler/README.md

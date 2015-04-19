# HTML Styleguide

## Some General Guidelines

 - Each `<section>` and `<article>` start their own header scope, so the top level heading within each will be an `<h1>`.
 - `<section>` tags are for major sections of page content. If in doubt, use a `<div>`
 - There is no need for `<header>` tags if they only contain a single element (e.g. `<h1>`)
 - Do not use HTML elements for their style (e.g. don't use an `<h1>` tag because it is the size you want).
 - Use the [HTML Outline Chrome extension](https://chrome.google.com/webstore/detail/html5-outliner/afoibpobokebhgfnknfndkgemglggomo?utm_source=chrome-ntp-icon) to ensure that the page is well structured.
 - If something isn't covered in this guide, check out the source for [bbc.com](http://www.bbc.com), [The Guardian](http://www.theguardian.com/au) or the [Boston Globe](http://www.bostonglobe.com). They all have decent site structure.

## Single Article
See the [article.html](article.html) file for a sample structure.

 - A page with a single article should have a single `<article>` tag as the root of the article.
 - If the article itself has structure, define this through the use of header tags. 

## List of Articles
See the [article-list.html](article-list.html) file for a sample structure.

 - A page with a list of articles could be a homepage, tag page, search results page, etc. The page may or may not be broken into sub-sections.
 - Each article should be wrapped in an `<article>` tag with its own `<h1>`.

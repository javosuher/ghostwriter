# Ghostwriter

Enhanced port of the Ghost "[ghostwriter](https://github.com/roryg/ghostwriter)" theme to the [Hugo](http://gohugo.io) site generator. Created by [Juraj Bubniak](https://github.com/jbub) and forked from his [repository](https://github.com/jbub/ghostwriter).

## Installation

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/javosuher/ghostwriter

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Example config.toml

To customize your theme you can use following params:

```toml
baseurl = "http://example.com/"
title = "mytitle"
theme = "ghostwriter"
languageCode = "en-us"
copyright = "My Name"
googleAnalytics = "XXX"
disqusShortname = "XXX"

[Author]
    name = "My Name"
    profile = "https://google.com/+XXX"

[Taxonomies]
    tag = "tags"

[Params]
    intro = true
    icon = "img/web-icon.png"
    github = "https://github.com/XXX"
    linkedin = "https://linkedin.com/in/XXX/"
    gplus = "https://google.com/+XXX"
    twitter = "https://twitter.com/XXX"
    stackoverflow = "http://stackoverflow.com/users/XXX/YYY"
    completeTitle = "<span>Ghost</span>writer example Web<span>site</span>"
    headline = "Ghostwriter example"
    description = "Ghostwriter example description"

[Permalinks]
    post = "/:year/:month/:day/:filename/"

[[menu.main]]
    name = "Blog"
    url = "/"
    weight = 1

[[menu.main]]
    name = "Projects"
    url = "/project/"
    weight = 2

[[menu.main]]
    name = "Contact"
    url = "/page/contact/"
    weight = 3

[[menu.main]]
    name = "About"
    url = "/page/about/"
    weight = 4
```

# Hello, Hugo!

This is a skeleton theme for starting a new [Hugo](https://gohugo.io) project.

It's basically what I wish happened when you do `hugo new theme`. Bare bones, no styles, no nothing,
but all the important files are there in their most basic (but working) state.

## How to use

```
hugo new site foo
cd foo
git clone --depth 1 https://github.com/i40west/hello-hugo themes/hello-hugo
```

Edit your `config.toml` to add:

```
theme = 'hello-hugo'
```

Then:

```
hugo new posts/hello.md
```

Edit the `content/posts/hello.md` file to get rid of `draft: true` and add some content.

```
hugo server
```

...and behold the beauty of localhost:1313. Then get to work!

## And honestly...

I probably did something wrong, left something out, or overlooked something I don't
even know about or didn't think of. It can probably be improved, is what I'm saying.

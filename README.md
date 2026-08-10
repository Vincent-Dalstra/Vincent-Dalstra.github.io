# vincent-dalstra.github.io

Shamelessly ripped from: https://github.com/matklad/matklad.github.io

Mainly for the server-based rss reader pattern: https://matklad.github.io/2025/06/26/rssssr.html

## Original:

Source code for the blog. The `./src` directory contains a deno script that reads `.djot` from
`./content` and writes `.html` to `./out`.

```console
$ deno task build
$ deno task serve
```

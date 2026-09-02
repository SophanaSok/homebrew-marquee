# homebrew-marquee

A Homebrew tap for [marquee-markdown](https://github.com/SophanaSok/marquee-markdown) —
a terminal markdown reader with the functionality of `glow`, rendering documents
the way Claude artifacts do, with a table-of-contents panel.

```sh
brew install SophanaSok/marquee/marquee-markdown
```

That installs two commands, `marquee-markdown` and `mmd`, which are the same
program under a shorter name, along with man pages and shell completions for
both.

The formula builds from the tag's source tarball with cargo. It lives in the
main repository at `packaging/homebrew/marquee-markdown.rb`, where a test
fails if it falls two releases behind — this tap is where it is published,
not where it is maintained.

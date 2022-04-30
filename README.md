# mdbook SVG Stylesheet

Example book to use SVG stylesheets with [`mdbook-graphviz`].

## Building Locally

See below for OS specific commands.

1. Install [`mdbook`].
2. Install [`mdbook-graphviz`].
3. Install [`graphviz`]
4. Run `mdbook serve`.
5. Open http://localhost:3000

### Linux

```bash
sudo apt install graphviz
cargo install mdbook
cargo install mdbook-graphviz
mdbook serve
```

### Mac / OS X

```bash
brew install graphviz
cargo install mdbook
cargo install mdbook-graphviz
mdbook serve
```

[`mdbook`]: https://github.com/rust-lang/mdBook
[`mdbook-graphviz`]: https://github.com/dylanowen/mdbook-graphviz
[`graphviz`]: https://www.graphviz.org/download/

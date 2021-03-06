[JSDD](../README.md) &gt; Make your own documentation with markdown

# Make your own documentation

Writing down documentation whenever you find a way to do something new is a good way to memorize and learn.

## Markdown

I use the [Markdown syntax](http://daringfireball.net/projects/markdown/syntax) (.md files) to write down my documentation.
However stated so on [this page](https://help.github.com/articles/github-flavored-markdown), it seems that GitHub basic .md files display doesn't totally apply the [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/) syntax, hence a double paragraph character is necessary to display separated lines.

You may want to visualize your markdown files before pushing them online:

- [Chrome extension](https://chrome.google.com/webstore/detail/markdown-preview/jmchmkecamhbiokiopfpnfgbidieafmd?hl=en) (click on FREE+ at top-right to install). This doesn't implement the [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/) syntax.

- [Windows installer](https://bitbucket.org/wcoenen/downmarker/downloads)

Or you can use this very simplistic solution actually providing these pages:

- .htaccess: to redirect *.md to md.php in root directory (defaults to README.md)
- Parsedown.php: a php md parser class (thanks to Emanuil Rusev)
- md.php: a little script to glue it all

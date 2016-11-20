*Forked from [vimscript#529](http://www.vim.org/scripts/script.php?script_id=529)*

BlockQuote.vim
==============

Insert block quotes like emacs blockquote.el

Examples
--------

With a title:

```text
,----[ title ]-
| some text
`----
```

Without a title:

```text
,----
| some text
`----
```

Usage
-----

Blockquote a range *(default: current line)*:

```
:[range]BlockQuote {title}
```

Blockquote a file:

```
:BlockQuoteFile {filename}
```

Blockquote a file, starting at line `{start}`:

```
:BlockQuoteFile {filename} {start}
```

Blockquote a file, starting at line `{start}` and ending at `{end}`:

```
:BlockQuoteFile {filename} {start} {end}
```

Remove a blockquote, starting at `[range]` *(default: current line)*:

```
:[range]BlockUnQuote
```

Credits
-------

Created by [Andreas Ferber](http://www.vim.org/account/profile.php?user_id=1374)

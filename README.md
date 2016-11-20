*Forked from [vimscript#529](http://www.vim.org/scripts/script.php?script_id=529)*

blockquote.vim
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
:<range>Bq [title]
```

Blockquote a file:

```
:Bqf {filename}
```

Blockquote a file, starting at line `{start}`:

```
:Bqf {filename} {start}
```

Blockquote a file, starting at line `{start}` and ending at `{end}`:

```
:Bqf {filename} {start} {end}
```

Remove a blockquote, starting at `<range>` *(default: current line)*:

```
:<range>UBq
```

Credits
-------

Created by [Andreas Ferber](http://www.vim.org/account/profile.php?user_id=1374)

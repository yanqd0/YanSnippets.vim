# snippets-for-vim

[![Release](https://img.shields.io/github/release/yanqd0/vimfiles.svg)][Releases]

This is a collection of my personal snippets in Vim.

## Install

Make sure the Vim plug-in [SirVer/ultisnips][ultisnips] is installed and accessable in your Vim editor.
If you use [Vundle.vim][Vundle.vim], it is like this:

```vim
Plugin 'SirVer/ultisnips'
Plugin 'yanqd0/snippets-for-vim'
```

`UltiSnips` is the default path of [SirVer/ultisnips][ultisnips] If you changed that, make sure `UltiSnips` is always included in your `vimrc`.

```vim
let g:UltiSnipsSnippetDirectories = [
            \ "your_personal_snippets_directory",
            \ "UltiSnips"
            \ ]
```

## Content

### Vim

| Trigger    | Description                 |
| :------    | :----------                 |
| helloworld | A basic "Hello world!" demo |
| function   | A `function` block          |
| if         | `if` block                  |
| ife        | `if else` block             |
| ifi        | `if elseif` block             |
| ifie       | `if elseif else` block        |
| todo       | `# TODO` comment            |
| fixme      | `# FIXME` comment           |
| xxx        | `# XXX` comment             |

### Java

| Trigger    | Description                            |
| :------    | :----------                            |
| helloworld | A basic "Hello world!" demo            |
| class      | A public class, named after file       |
| iclass     | A inner class                          |
| interface  | A interface                            |
| if         | `if () {}` block                       |
| ife        | `if () {} else () {}` block            |
| ifi        | `if () {} else if () {}` block         |
| ifie       | `if () {} else if () {} else {}` block |
| do         | `do {} while ();` block                |
| while      | `while () {}` block                    |
| for        | `for () {}` block                      |
| tryc       | `try {} catch() {}` block              |
| tryf       | `try {} finally {}` block              |
| trycf      | `try {} catch() {} finally {}` block   |
| sync       | `synchronized () {}` block             |
| todo       | `// TODO` comment                      |
| fixme      | `// FIXME` comment                     |
| xxx        | `// XXX` comment                       |

### Python

| Trigger    | Description                 |
| :------    | :----------                 |
| helloworld | A basic "Hello world!" demo |
| #!         | `#!` block, file header     |
| main       | __main__ block              |
| class      | A new class                 |
| if         | `if` block                  |
| ife        | `if else` block             |
| ifi        | `if elif` block             |
| ifie       | `if elif else` block        |
| while      | `while` block               |
| for        | `for in` block              |
| trye       | `try except` block          |
| tryf       | `try finally` block         |
| tryef      | `try except finally` block  |
| todo       | `# TODO` comment            |
| fixme      | `# FIXME` comment           |
| xxx        | `# XXX` comment             |

### Shell

| Trigger    | Description                 |
| :------    | :----------                 |
| helloworld | A basic "Hello world!" demo |
| #!         | `#!` block, file header     |
| function   | A `function` block          |
| if         | `if` block                  |
| ife        | `if else` block             |
| ifi        | `if elif` block             |
| ifie       | `if elif else` block        |
| case       | `case esac` block           |
| select     | `select do done` block      |
| until      | `until do done` block       |
| while      | `while do done` block       |
| for        | `for do done` block         |
| todo       | `# TODO` comment            |
| fixme      | `# FIXME` comment           |
| xxx        | `# XXX` comment             |

### snippets

| Trigger | Description         |
| :------ | :----------         |
| snip    | Add a new snippet.  |
| glob    | Add a global block. |

### all

| Trigger   | Description                                           |
| :------   | :----------                                           |
| MIT       | Add a MIT License full text.                          |
| Apache2   | Add an Apache License 2.0 full text.                  |
| #Apache2  | Add a `# comment` header of Apache2 .                 |
| /*Apache2 | Add a `/* comment */` header of Apache2 .             |
| !-Apache2 | Add a `<!-- comment -->` header of Apache2 .          |
| GPLv2     | Add a GNU General Public License Version 2 full text. |
| #GPLv2    | Add a `# comment` header of GPLv2 .                   |
| /*GPLv2   | Add a `/* comment */` header of GPLv2 .               |
| !-GPLv2   | Add a `<!-- comment -->` header of GPLv2 .            |
| GPLv3     | Add a GNU General Public License Version 3 full text. |
| #GPLv3    | Add a `# comment` header of GPLv3 .                   |
| /*GPLv3   | Add a `/* comment */` header of GPLv3 .               |
| !-GPLv3   | Add a `<!-- comment -->` header of GPLv3 .            |

## License

[![License](https://img.shields.io/github/license/yanqd0/snippets-for-vim.svg)](LICENSE)

> The MIT License (MIT)
>
> Copyright (c) 2016 yanqd0@outlook.com

[Releases]:https://github.com/yanqd0/snippets-for-vim/releases/latest
[ultisnips]:https://github.com/SirVer/ultisnips
[Vundle.vim]: https://github.com/VundleVim/Vundle.vim

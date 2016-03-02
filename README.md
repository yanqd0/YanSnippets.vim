# snippets-for-vim

## Introduction

This is a collection of my personal general snippets in Vim.

## Install

Make sure the Vim plug-in [UltiSnips][1] is installed and accessable in your Vim editor. If you use [Vundle.vim][2], it is like this:

```VimL
Plugin 'SirVer/ultisnips'
Plugin 'yanqd0/snippets-for-vim'
```

`UltiSnips/` is the default path of [UltiSnips][1]. If you changed that, make sure `UltiSnips/` is always included in your `vimrc`.

```VimL
let g:UltiSnipsSnippetDirectories = [
            \ "your_personal_snippets_directory",
            \ "UltiSnips"
            \ ]
```

## Content

### Java

| Trigger    | Description                            |
| :------    | :----------                            |
| helloworld | A basic "Hello world!" demo            |
| nclass     | A public class, named after file       |
| iclass     | A inner class                          |
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
| nclass     | A new class                 |
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
| if         | `if` block                  |
| ife        | `if else` block             |
| ifi        | `if elif` block             |
| ifie       | `if elif else` block        |
| case       | `case esac` block           |

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

This [repository][0] is under the [MIT License][3].

Copyright © 2015 yanqd0@gmail.com

[0]: https://github.com/yanqd0/snippets-for-vim
[1]: https://github.com/SirVer/ultisnips
[2]: https://github.com/VundleVim/Vundle.vim
[3]: http://choosealicense.com/licenses/mit/

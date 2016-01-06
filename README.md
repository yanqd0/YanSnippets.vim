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
| helloworld | A basic "Hello world!"                 |
| nclass     | A public class, named after file.      |
| iclass     | A inner class.                         |
| if         | `if () {}` block                       |
| ife        | `if () {} else () {}` block            |
| ifi        | `if () {} else if () {}` block         |
| ifie       | `if () {} else if () {} else {}` block |
| do         | `do {} while ();` block                |
| while      | `while () {}` block                    |
| tryc       | `try {} catch() {}` block              |
| tryf       | `try {} finally {}` block              |
| trycf      | `try {} catch() {} finally {}` block   |
| sync       | `synchronized () {}` block             |
| TODO       | `// TODO` comment                      |
| FIXME      | `// FIXME` comment                     |
| XXX        | `// XXX` comment                       |

### snippets

| Trigger | Description         |
| :------ | :----------         |
| snip    | Add a new snippet.  |
| glob    | Add a global block. |


## License

This is under the [MIT License][3].

©  2015 yanqd0@gmail.com

[1]: https://github.com/SirVer/ultisnips
[2]: https://github.com/VundleVim/Vundle.vim
[3]: http://choosealicense.com/licenses/mit/

# snippets-for-vim

## Introduction

This is a collection of my personal general snippets in Vim.

## Dependency

Make sure the Vim plug-in [UltiSnips][1] is installed and accessable in Vim editor. If you use [Vundle.vim][2], it like this:

```VimL
Plugin 'SirVer/ultisnips'
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
| TODO       | `// TODO` comment                      |
| FIXME      | `// FIXME` comment                     |
| XXX        | `// XXX` comment                       |

## License

This is under the [MIT License][3].

©  2015 yanqd0@gmail.com

[1]: https://github.com/SirVer/ultisnips
[2]: https://github.com/VundleVim/Vundle.vim
[3]: http://choosealicense.com/licenses/mit/

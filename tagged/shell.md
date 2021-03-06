## Bookmarks tagged [[shell]](https://www.codever.land/search?q=[shell])

_<sup><sup>[www.codever.land/bookmarks/t/shell](https://www.codever.land/bookmarks/t/shell)</sup></sup>_
---
#### [shell - Which terminal command to get just IP address and nothing else? - Stack Overflow](https://stackoverflow.com/questions/8529181/which-terminal-command-to-get-just-ip-address-and-nothing-else)
_<sup>https://stackoverflow.com/questions/8529181/which-terminal-command-to-get-just-ip-address-and-nothin...</sup>_

On OSX, if you know the interface, you could use - `$ ipconfig getifaddr en0`

You can write a script that only return the IP like:
...
* **tags**: [shell](../tagged/shell.md), [osx](../tagged/osx.md), [linux](../tagged/linux.md), [ipaddress](../tagged/ipaddress.md), [networking](../tagged/networking.md)
---
#### [awesome-shell](https://github.com/alebcay/awesome-shell#readme)
_<sup>https://github.com/alebcay/awesome-shell#readme</sup>_

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. - alebcay/awesome-shell
* **tags**: [awesome-list](../tagged/awesome-list.md), [shell](../tagged/shell.md)
* :octocat: **[source code](https://github.com/alebcay/awesome-shell#readme)**
---
#### [command line - How to list all symbolic links in a directory - Ask Ubuntu](https://askubuntu.com/questions/522051/how-to-list-all-symbolic-links-in-a-directory)
_<sup>https://askubuntu.com/questions/522051/how-to-list-all-symbolic-links-in-a-directory</sup>_

```
find . -type l -ls
```

To only process the current directory:
```
find . -maxdepth 1 -type l -ls
```
* **tags**: [bash](../tagged/bash.md), [shell](../tagged/shell.md), [linux](../tagged/linux.md)
---
#### [Oh My Zsh](https://ohmyz.sh/)
_<sup>https://ohmyz.sh/</sup>_

Oh-My-Zsh is a delightful, open source, community-driven framework for managing your ZSH configuration.
* **tags**: [shell](../tagged/shell.md), [zsh](../tagged/zsh.md), [tools](../tagged/tools.md)
* :octocat: **[source code](https://github.com/robbyrussell/oh-my-zsh)**
---
#### [How to symlink a file in Linux? - Stack Overflow](https://stackoverflow.com/questions/1951742/how-to-symlink-a-file-in-linux)
_<sup>https://stackoverflow.com/questions/1951742/how-to-symlink-a-file-in-linux</sup>_

To create a new symlink (will fail if symlink exists already):

* **tags**: [linux](../tagged/linux.md), [shell](../tagged/shell.md)
---
#### [command line - How to show only hidden files in Terminal? - Ask Ubuntu](https://askubuntu.com/questions/468901/how-to-show-only-hidden-files-in-terminal)
_<sup>https://askubuntu.com/questions/468901/how-to-show-only-hidden-files-in-terminal</sup>_

The command to show only hidden files:

* **tags**: [linux](../tagged/linux.md), [shell](../tagged/shell.md)
---
#### [shell - How to scp a folder from remote to local? - Stack Overflow](https://stackoverflow.com/questions/11304895/how-to-scp-a-folder-from-remote-to-local)
_<sup>https://stackoverflow.com/questions/11304895/how-to-scp-a-folder-from-remote-to-local</sup>_

```
scp -r user@your.server.example.com:/path/to/foo /home/user/Desktop/
```

`-r` **Recursively** copy entire directories


* **tags**: [scp](../tagged/scp.md), [shell](../tagged/shell.md)
---
#### [Pequena introdu????o ao linux e ao Shell Script ](https://www.telecom.uff.br/pet/petws/downloads/apostilas/LINUX.pdf)
_<sup>https://www.telecom.uff.br/pet/petws/downloads/apostilas/LINUX.pdf</sup>_

(PDF)
* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-pt_br](../tagged/free-programming-books-pt_br.md)
---
#### [Introdu????o ao Shell Script](http://aurelio.net/shell/apostila-introducao-shell.pdf)
_<sup>http://aurelio.net/shell/apostila-introducao-shell.pdf</sup>_

Aurelio Marinho Jargas (PDF)
* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-pt_br](../tagged/free-programming-books-pt_br.md)
---
#### [The Linux Command Line ?????????](http://billie66.github.io/TLCL/book/zh)
_<sup>http://billie66.github.io/TLCL/book/zh</sup>_

* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-zh](../tagged/free-programming-books-zh.md)
---
#### [Shell ????????????30????????????](https://github.com/qinjx/30min_guides/blob/master/shell.md)
_<sup>https://github.com/qinjx/30min_guides/blob/master/shell.md</sup>_

* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-zh](../tagged/free-programming-books-zh.md)
---
#### [Shell ????????????](http://wiki.ubuntu.org.cn/Shell%E7%BC%96%E7%A8%8B%E5%9F%BA%E7%A1%80)
_<sup>http://wiki.ubuntu.org.cn/Shell%E7%BC%96%E7%A8%8B%E5%9F%BA%E7%A1%80</sup>_

* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-zh](../tagged/free-programming-books-zh.md)
---
#### [shell-book](http://me.52fhy.com/shell-book/)
_<sup>http://me.52fhy.com/shell-book/</sup>_

* **tags**: [free-programming-books](../tagged/free-programming-books.md), [shell](../tagged/shell.md), [free-programming-books-zh](../tagged/free-programming-books-zh.md)
---
#### [How to find all files containing specific text on Linux? - Stack Overflow](http://stackoverflow.com/questions/16956810/how-to-find-all-files-containing-specific-text-on-linux)
_<sup>http://stackoverflow.com/questions/16956810/how-to-find-all-files-containing-specific-text-on-linux</sup>_

```
grep -rnw '/path/to/somewhere/' -e "pattern"
```

* `-r` or `-R` is recursive,
* `-n` is line number, and
* `-w` stands for match the whole word.
* `-l` (lower-case L) can be added to just give th...
* **tags**: [linux](../tagged/linux.md), [shell](../tagged/shell.md)
---

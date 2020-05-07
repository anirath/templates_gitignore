# Anirath's Templates -- Gitignore #
**GitHub Repository -- [anirath/templates_gitignore][1]**

**Anirath's Homepage -- [anirath.github.io][18]**

## Readme ##
This project is a collection of templates for use with [gitignore][2]. Originally, the repository was forked
from [github/gitignore][3]. The templates from the [source repository][3] were mostly deleted, consolidated,
and then reorganized to my preferred [structure](#Folder-Structure). This particular project isn't meant to
contribute to the initial [forked project][3], and will continue to be developed as needed and used.

Projects and repositories of mine with the **templates_** and **modules_** prefixes are *primarily* meant for
my own usage during development, configuration, etc. However, they are typically still *public* repositories,
and other users are more than welcome to use them, modify them, fork them, and/or do whatever they want with
them so long as it abides by the corresponding *license*.

## Folder Structure ##
- [Root](./) -- The project's root directory. Contains a *symlink* to the [Readme][src_2] and [License][src_3].
- [./docs/](./docs/) -- All of the [documentation][src_4] for this project.
- [./src/](./src/) -- Contains all of the [source files][src_1] for this project.
- [./src/languages/](./src/languages/) -- Templates for various programming and scripting languages.
- [./src/misc/](./src/misc/) -- Templates for miscellaneous purposes. *(e.g. Images, SVN, etc.)*
- [./src/platforms/](./src/platforms/) -- Templates for any platforms, software, and frameworks. *(e.g. Windows, Jekyll, Godot, etc.)*

## Template List ##
### Languages ###
*The following templates can be found at:* [./src/languages/](./src/languages/)
- [C](./src/languages/c.gitignore) : `c.gitignore` -- For the [C Programming Language][7].
- [C++](./src/languages/c++.gitignore) : `c++.gitignore` -- For the [C++ Programming Language][8].
- [Java](./src/languages/java.gitignore) : `java.gitignore` -- For the [Java Programming Language][9].
- [Python](./src/languages/python.gitignore) : `python.gitignore` -- For the [Python Programming Language][10].

## Misc ##
*The following templates can be found at:* [./src/misc/](./src/misc/)
- [Archives](./src/misc/archives.gitignore) : `archives.gitignore` -- Template for various archive files.
- [Backups](./src/misc/backups.gitignore) : `backups.gitignore` -- Template for any backup and temp files.
- [Images](./src/misc/images.gitignore) : `images.gitignore` -- Covers any common image filetypes.
- [OpenSSL](./src/misc/openssl.gitignore) : `openssl.gitignore` -- [OpenSSL][11] related files.
- [SVN](./src/misc/svn.gitignore) : `svn.gitignore` -- Covers files used by [SVN][12].

## Platforms ##
*The following templates can be found at:* [./src/platforms/](./src/platforms/)
- [Godot](./src/platforms/godot.gitignore) : `godot.gitignore` -- The open source game engine [Godot][13].
- [Jekyll](./src/platforms/jekyll.gitignore) : `jekyll.gitignore` -- The static site generator [Jekyll][14].
- [Node.js](./src/platforms/node.gitignore) : `node.gitignore` -- The [JavaScript][15] runtime [Node.js][16].
- [Windows](./src/platforms/windows.gitignore) : `windows.gitignore` -- Common files from the [Windows OS][17].

## External Resources ##
- [Pro Git Book][5]
- [Pro Git Book: Ignoring Files Chapter][6]
- [GitHub Help: Ignoring Files][4]
- [Manpages: gitignore(5)][3]


[src_1]: https://github.com/anirath/templates_gitignore/blob/master/src/
[src_2]: https://github.com/anirath/templates_gitignore/blob/master/docs/readme.md
[src_3]: https://github.com/anirath/templates_gitignore/blob/master/docs/license.txt
[src_4]: https://github.com/anirath/templates_gitignore/blob/master/docs/

[1]: https://github.com/anirath/templates_gitignore/
[2]: http://git-scm.com/docs/gitignore
[3]: https://github.com/github/gitignore/
[4]: https://help.github.com/articles/ignoring-files
[5]: http://git-scm.com/book
[6]: https://git-scm.com/book/en/Git-Basics-Recording-Changes-to-the-Repository#_ignoring
[7]: https://en.wikipedia.org/wiki/C_(programming_language)
[8]: https://isocpp.org/
[9]: https://www.oracle.com/java/
[10]: https://www.python.org/
[11]: https://www.openssl.org/
[12]: https://subversion.apache.org/
[13]: https://godotengine.org/
[14]: https://jekyllrb.com/
[15]: https://en.wikipedia.org/wiki/JavaScript
[16]: https://nodejs.org/
[17]: https://www.microsoft.com/en-us/windows
[18]: https://anirath.github.io/

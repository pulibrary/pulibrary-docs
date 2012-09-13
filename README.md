pulibrary-docs
==============

This is a repository of Documentation (Best Practices, How-to's, etc.) for the [Princeton University Library](http:/github.com/pulibrary) organization.  It is basically a pile of Github Flavored Markdown files that emulate a wiki.  Team members can edit any of the files through the Github interface, but new files need to be created in a cloned repository and pushed (see How to Contribute).  Same goes for the deletion of files.  

Like files can be grouped together in sub-directories.  Subdirectories with multiple files should have a standard index page with links and descriptions.  In addition to the creation and deletion of files, one of the other main differences between this wiki-like approach and traditional  wikis is that links to other .md files within this repository must be hardcoded like so:
``` [my link](https://github.com/pulibrary/pulibrary-docs/blob/master/git-help.md) ```

_P.S. "Stubs" can be created, but they will point to a 404._

## How to contribute

To contribute to this documentation, you must clone this repository and [contribute as you would](https://github.com/pulibrary/pulibrary-docs/blob/master/git-help.md) any other code repository for pulibrary.  

After that, you have three options for editing files:
* Be a rockstar and edit the files by hand in vi (or your favorite editor) without a preview net! (Use at your own risk!)
* Use a combo of your favorite editor and [Github Markdown Live Preview](https://github.com/github/github-flavored-markdown) _Note: The [online utility](http://github.github.com/github-flavored-markdown/preview.html) is currently down to fix a [xss problem](https://github.com/github/github-flavored-markdown/issues/56). Use [this fork](http://tmpvar.com/markdown.html) in the meantime._
* Use [Gollum](https://github.com/pulibrary/puldocs).  Gollum is a wiki that uses Git as its engine.  It's what Github uses for its own wikis.  The advantage of Gollum is that it more closely resembles a traditional wiki.  The downside is that you need to install the ruby app on your dev machine.  Another problem is that Gollum adds a bit of clutter in the form of its own code.  To maintain the purity of the "pile of .md files", you could clone the pulibrary-docs (this repo) inside of a subdirectory in Gollum using [submodules](http://git-scm.com/book/en/Git-Tools-Submodules).  _This needs to be tested._  Simple code enhancements could enable automated syncing (pushes and pulls through the github api) and relative links and stubbing. 

## Documents

* [Best practices for collaborative development with Git](https://github.com/pulibrary/pulibrary-docs/blob/master/git-help.md)
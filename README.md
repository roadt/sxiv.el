<a href="https://liberapay.com/contrapunctus/donate"><img alt="Donate using Liberapay" src="https://img.shields.io/liberapay/receives/contrapunctus.svg?logo=liberapay"></a>

<a href="https://melpa.org/#/sxiv"><img src="https://melpa.org/packages/sxiv-badge.svg"></a>

# sxiv.el
Launch [sxiv](https://github.com/muennich/sxiv) (Simple X Image Viewer) from Emacs, with Dired integration.

## Installation
You can get `sxiv.el` from

`sxiv.el` requires [dash.el](https://github.com/magnars/dash.el) and an installed [sxiv](https://github.com/muennich/sxiv) in your $PATH

## Usage
The main command is `M-x sxiv`.

Run it in a Dired buffer containing images. Files marked in sxiv (mark/unmark with `m`) will be marked in Dired.

If the Dired buffer has marked files, open only those files.

With prefix argument, or when only provided directories, run recursively.

Run it from a text file containing one file name per line to open the listed files.

## Limitations
* `sxiv-dired-marked-files-p` doesn't work as intended with non '*' markers (e.g. C or D)

## Comparison with [picpocket](https://github.com/johanclaesson/picpocket)
At a cursory glance, picpocket (v20180914)
* ✔️ does not depend on an external program
* ✔️ has better key customizability (to change the keys for sxiv itself, you need to modify its C source)
* ✔️ supports tagging images
* ✖️ has no way to mark files for batch operations
* ✖️ does not seem to center images in fullscreen mode

## Contributions and contact
Feedback and MRs very welcome. 🙂

You may be interested in the [TODO.md](TODO.md)

Contact the creator and other Emacs users in the Emacs room on the Jabber network - [xmpp:emacs@salas.suchat.org?join](xmpp:emacs@salas.suchat.org?join) ([web chat](https://inverse.chat/#converse/room?jid=emacs@salas.suchat.org))

(For help in getting started with Jabber, [click here](https://xmpp.org/getting-started/))

## License
I dream of a world where all software is liberated - transparent, trustable, and accessible for anyone to use or improve. But I don't want to make demands or threats (e.g. via legal conditions) to get there.

I'd rather make a request - please do everything you can to help that dream come true. Please Unlicense as much software as you can.

sxiv.el is released under your choice of [Unlicense](https://unlicense.org/) or the [WTFPL](http://www.wtfpl.net/).

(See files [UNLICENSE](UNLICENSE) and [WTFPL](WTFPL)).

## Thanks
wasamasa, bpalmer and #emacs for all their help and support

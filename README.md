# vim-reason-runtime

Runtime files (ftdetect, indent, syntax) for [Reason] Language.

This is a copy of relevant parts of [jordwalke/vim-reasonml][] for those use
case where you only want simple support for Reason Language and not the entire
Merlin runtime.

Use [jordwalke/vim-reasonml][] if you need autocompletion, diagnostics and other
goodies out of the box.

## Installation

I use [vim-plug][] and recommend it unless you settled with another plugin
manager:

    Plug 'arrowresearch/vim-reason'

## Development

To update runtimes files from upstream:

    git submodule init
    git submodule update
    make promote

Make sure you review and commit them.

[Reason]: https://reasonml.github.io
[jordwalke/vim-reasonml]: https://github.com/jordwalke/vim-reasonml
[vim-plug]: https://github.com/junegunn/vim-plug

# vim-reason-runtime

Runtime files (ftdetect, indent, syntax) for [Reason] Language.

This is just a copy of relevant parts of [jordwalke/vim-reasonml][] for those use
case where you only want simple support for Reason Language and not the entire
Merlin runtime.

## Installation

I use [vim-plug][] and recommend it unless you settled with another option:

    Plug 'andreypopp/vim-reason-runtime'

## Development

To update runtimes files from upstream:

    git submodule init
    git submodule update
    make promote

Make sure you review and commit them.

[Reason]: https://reasonml.github.io
[jordwalke/vim-reasonml]: https://github.com/jordwalke/vim-reasonml
[vim-plug]: https://github.com/junegunn/vim-plug

Scripts to Generate Dash Docsets
================================

This is a collection of scripts to download and index various
documentation to [Dash][1] docset format. Results have been tested to
work with Emacs and [helm-dash][2], but will probably work with all
applications that support the docset format.

[1]: https://kapeli.com/docsets
[2]: https://github.com/areina/helm-dash

To generate these docsets, you'll need Wget, Python 3, Requests and
Beautiful Soup 4 (bs4). To generate a docset, e.g. Python, run
`./build Python.docset`; to generate all docsets, run `./build *.docset`.

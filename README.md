# CollapseOS documentation browser

This is a tool to generate browsable HTML documentation for CollapseOS.

There is a live version viewable at https://incoherency.co.uk/collapseos/ .

If you don't know what CollapseOS is, see http://collapseos.org/ .

To generate documentation for the latest snapshot, run `./run`. You'll get the HTML
under `collapseos/`.

If it is generating some bad HTML, the bug is probably in the `htmlify()` function in `mk-html-doc`.

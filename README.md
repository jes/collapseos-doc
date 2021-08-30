# Collapse OS documentation browser

This is a tool to generate browsable HTML documentation for Collapse OS.

There is a live version viewable at https://incoherency.co.uk/collapseos/ .

If you don't know what Collapse OS is, see http://collapseos.org/ .

To generate documentation for the latest snapshot, run `./run`. You'll get the HTML
under `collapseos/`. You'll need `Template::Toolkit`.

If it is generating some bad HTML, the bug is probably in the `htmlify()` function in `mk-html-doc`.

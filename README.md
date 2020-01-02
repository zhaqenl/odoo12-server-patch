odoo12-server-patch
===================

This is a `process_python` function patch for the `server.py` file under the
`service` directory of an odoo 12 installation, for those that use `emacs` as
their text editor and those that develop using odoo 12’s `--dev=all` option, at
the same time. Not applying this patch results in an uncaught `IOError` due to
emacs generating `*.py` files that start with `.#`, hence the file not being
found.

BoxMaker Web App
================

A simple web front-end to the BoxMaker command line tool for making designs you can laser-cut.

Forked by NuVu, to make it more efficient in its exports and add various other features.

Dependencies
------------

```
pip install reportlab
pip install flask
```

Installation
------------

2. Make the `tmp` directory writable by your web user

Running
-------

Just run `python server.py` and then try it at http://localhost:5000 in your web browser.

If you want to render a box in code, see the `test-render.py` example.

License
-------

This software is released under the [http://www.gnu.org/licenses/agpl.html](GNU Affero General Public License).

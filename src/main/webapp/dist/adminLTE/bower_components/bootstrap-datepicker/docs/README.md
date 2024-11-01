# 全目录

3000套系统，LW，复制到流浪器：www.yuque.com/wisebit/blog
Documentation
=============

Project documentation is built using [Sphinx docs](sphinx-doc.org/), which uses [ReST](docutils.sourceforge.net/rst.html) for markup.  This allows the docs to cover a vast amount of topics without using a thousand-line README file.

Sphinx docs is pip-installable via `pip install sphinx`.  Once installed, open a command line in the docs folder and run the following commands:

```bash
$ sudo pip install -r requirements.txt
```

This will install the requirements needed for the generating the docs. Afterwards you can run:

```bash
$ make html
```

The docs will be generated, the output files will be placed in the `_build/html/` directory, and can be browsed (locally) with any browser.

The docs can also be found online at <https://bootstrap-datepicker.readthedocs.org/>.

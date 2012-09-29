Export [Day One][0] journal entries into html, text, or another format
using a Jinja template.

by Nathan Grigg

# Installation

Use [pip][4]:

    pip install dayone_export

You can also use easy install
(`easy_install dayone_export`)
or download the source and install
(`python setup.py install`).


Any of these methods will also install the dependencies
[Jinja2][1], [times][2], and [Markdown][3].

# Quick start

Export your entire journal with

    dayone_export --output journal.html /path/to/Journal.dayone

To see available options, run

    dayone_export --help

# Custom templates and advanced options

You can specify a custom template using the command line option `--template`.

You can permanently override the default template by creating a new template named `default.html` and saving it in the folder `~/.dayone_export`.

Full documentation and information about creating new templates is available at [Read the Docs][5].


[0]: http://dayoneapp.com
[1]: http://jinja.pocoo.org
[2]: http://pypi.python.org/pypi/times/
[3]: http://freewisdom.org/projects/python-markdown/
[4]: http://www.pip-installer.org/en/latest/index.html
[5]: http://day-one-export.readthedocs.org/

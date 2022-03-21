# Setup and Installation

- Must have Python v3.5+ installed.
- Must have mkdocs installed: `pip install mkdocs`
- Must have mkdocs theme- material installed: `pip install mkdocs-material`
- Clone the repository, `cd` in the repo
- Run ``mkdocs serve`` to get server running.
- Website should be available at: ``localhost:3000``

----

Building the pdf files reuire that weasy-print be installed. 
This will be installed as part of the pip command to install the theme.
However if by some chance(especially on windows), this does not work or you meet this error:
 #### OSError: cannot load library 'gobject-2.0-0': error 0x7e 
- you will need to install:GTK3 -> https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases
- Troubleshooting guide: https://doc.courtbouillon.org/weasyprint/latest/first_steps.html#windows


----

In the `mkdocs.yml` file.  **pdf-exports** has been commented out to speed up builds when you run `mkdocs serve`.
Keep in mind, if you wan to build the static file, you un-comment that line and run `mkdocs build`.



# defna.org
http://defna.org website

## Upload to GitHub Pages

Create a virtualenv and install our requirements.txt first:

    $ pelican content -s publishconf.py
    $ ghp-import output
    $ git push origin gh-pages
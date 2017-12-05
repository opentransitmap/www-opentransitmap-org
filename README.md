Testing
-------

This website is built using [Pelican](getpelican.com) and Python 3. For further information,
please check out the official [documentation](http://docs.getpelican.com/en/stable/index.html).

On Linux systems:
=================
* `pip3 install pelican markdown`
* `make devserver`
* Preview the site by navigating to http://localhost:8000/ in your browser.
It will automatically get updated on file changes.
* After testing, kill the local server using `./develop_server.sh stop`

Alternative Method for all operating systems:
=============================================
* `pip3 install pelican markdown fabric`
* `fab build && fab serve`
* Preview the site by navigating to http://localhost:8000/ in your browser.

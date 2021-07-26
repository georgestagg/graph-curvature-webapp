### Requirements ###
* Python 3+

### Installation Locally ###
To install the graph calculator locally, run the following commands in order.
* `git clone https://@mas-gitlab.ncl.ac.uk/graph-curvature/graph-curvature-webapp.git`
* `git clone https://@mas-gitlab.ncl.ac.uk/graph-curvature/graph-curvature-server.git`
* `cd graph-curvature-server`
* `python3 -m venv graph-curvature-venv`
* `source graph-curvature-venv/bin/activate`
* `pip install -r requirements.txt`
* Start the server: `python graph.py 8090&`
* `cd ../graph-curvature-webapp`
* Start the webapp server: `python -m SimpleHTTPServer&`

Then visit `http://localhost:8000` in your browser.

### Installation Online###
* Place these files somewhere on the public web.
* Install the [graph-curvature-server](https://mas-gitlab.ncl.ac.uk/graph-curvature/graph-curvature-server) and follow the instructions to start the server on a port (e.g. 8090)
* Edit the file `curvature.js` and change `localhost:8090` in the fist line to your server and port, e.g `teggers.eu:8090`.

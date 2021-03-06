## A script for plotting Strava data
See also https://nickdoornekamp.pythonanywhere.com/ and https://medium.com/@nddoornekamp/plotting-strava-data-with-python-7aaf0cf0a9c3

### Getting started
Note: the guide below was written for and tested on Linux. For running this on another OS, you might need to download the appropriate basemap.whl file from https://www.lfd.uci.edu/~gohlke/pythonlibs/. (E.g. f you're running 32-bit Windows with Python 3.6, take basemap‑1.2.1‑cp36‑cp36m‑win32.whl instead, and update environment.yml for that)
1. Run "conda env create --name strava-plotter-env -f environment.yml" and activate
2. Follow section B of [Strava's instructions for creating an app](https://developers.strava.com/docs/getting-started/). 
3. Rename '.env.example' to '.env' and fill the CLIENT_ID, CLIENT_SECRET you obtained in the previous steps.

### Running the the script
1. If desired, change the settings in settings.py
2. Run strava_plotter.py from the strava-plotter-env
3. Follow the instructions shown in the console

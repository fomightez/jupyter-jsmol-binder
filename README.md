[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/jupyter-jsmol-binder/master?filepath=index.ipynb)


# jupyter-jsmol-binder
The jupyter-jsmol extension able to be run in sessions served via MyBinder.org.

The jupyter-jsmol extension is JSmol viewer widget for Jupyter Notebooks and JupyterLab, see details provided by the jupyter-jsmol extension authors [here](https://github.com/fekad/jupyter-jsmol).

Click a 'launch binder' badge on this page to begin an active session where the jupyter-jsmol and the necessary dependencies are set to run.



Technical note
--------------

Simply, installing the extension in a running Binder session with pip didn't work, despite the ease the documentation suggesting that. Forunately the use of `requirements.txt` and `postBuild` enable installing and enabling properly.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/jupyter-jsmol-binder/master?filepath=index.ipynb)
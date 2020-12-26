Sphinx-Demo
===========

Installation
---------------
```
pip install -r requirements

cd docs
sphinx-quickstart
```

Configuration
-------------------

`conf.py`
```
import sphinx_rtd_theme
sys.path.insert(0, os.path.abspath('..'))

extensions = ['sphinx.ext.autodoc', 'sphinx.ext.coverage', 'sphinx.ext.napoleon',
              "sphinx_rtd_theme"]

html_theme = "sphinx_rtd_theme"
```

Start build server
-------------------------
```
sphinx-autobuild <project-dir>/docs <project-dir>/docs/_build/html
```

Links
-----------
* https://www.sphinx-doc.org/en/master/usage/extensions/autodoc.html#directive-automodule
* https://eikonomega.medium.com/getting-started-with-sphinx-autodoc-part-1-2cebbbca5365
* https://webdevops-documentation.readthedocs.io/en/latest/content/documentationWorkflow.html
* https://www.rizzonicola.com/sphinx-docker/
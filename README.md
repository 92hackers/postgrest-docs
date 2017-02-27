#### Sphinx source files for PostgREST documentation

To generate HTML version:

1. Install Sphinx from the [sphinx website](http://sphinx-doc.org/latest/install.html)
2. Clone this repository
4. Generate HTML
    ```bash
    cd postgrest-docs
    sphinx-build -b html -a -n . _build

    # open _build/index.html in your browser
    ```

---

**Sphinx Installation Notes:**

* If you're on OSX you might want to install the Python from homebrew - then a simple `pip install sphinx` does the trick.
* For an easier time refreshing your local preview of docs as you change it, try [sphinx-autobuild](https://github.com/GaretJax/sphinx-autobuild).

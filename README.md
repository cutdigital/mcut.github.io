# mcut-docs

Source code documentation for the MCUT project

## Setup

* Ensure you have `pip3` which is necessary to install the MkDocs theme that we use called [Material](https://github.com/squidfunk/mkdocs-material))
    - `curl https://bootstrap.pypa.io/get-pip.py | python`
    - `pip3 install --upgrade setuptools`
* Install MkDocs theme called "Material"
    - `sudo pip3 install mkdocs-material`
* Create build directory
    - `mkdir build && cd build` 
* Build the MCUT headers' documentation
    - `cmake .. && make`

## Previewing the site

* Serve website locally (http://127.0.0.1:8000/)
    - `mkdocs serve`

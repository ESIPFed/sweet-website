# SWEET website demo

Currently serving https://sweet.github.io

#### Proposal
This repo provides content for https://sweetontology.net  (eventual redirect)

#### Build the website using MkDocs

* Install [mkdocs](http://mkdocs.org) on your machine (see [installation instructions](http://www.mkdocs.org/#installation)).
* Install the [Cinder theme](https://github.com/chrissimpkins/cinder) (pip install mkdocs-cinder).
* Run the command `mkdocs gh-deploy` (or use deploy.sh).  
    * This command creates (or refreshes) the website at [https://sweet.github.io]().  
    * The command must be run from the root directory of this repo.  
    * Behind the scenes, `mkdocs gh-deploy` builds HTML docs from the Markdown sources, uses the `ghp-import` tool to commit them to the `gh-pages` branch, and pushes the `gh-pages` branch to GitHub.

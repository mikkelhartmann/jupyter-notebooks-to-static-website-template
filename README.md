# jupyter-notebooks-to-static-website-template
A template for generating a static website from a collection of notebooks.

This repo follows [this blogpost](www.mikkelhartmann.dk/2019/05/14/static-website-from-jupyter-notebooks.html). 

## Requirements
It is assumed that you have `conda` installed and that it works from the commandline. You will also need to have `make`. 

## Building
If you meet all the requirements you can build the environment by running

    make build.env

You should nove activate the environment by running

    conda activate static-site-generation

If you don't have conda you will simply need to get the packages listed in the `dependencies` part of `environment.yml` installed.

You can now build the static website by running

    make build.site

and browse it by running 

    mkdocs serve

This launches a site on you local host. Go to the link and click around.
# Civic Project

This project contains data on civic projects by Open Austin members. This is
inactive, but see the current list on the [projects page of the Open Austin
website](https://www.open-austin.org/projects/).

## projects Directory

The _projects_ directory contains descriptions of the projects, one file
per project. If you wish to add a project to the directory or update
information on an existing project, either:

* send us a pull request
* [open an issue](https://github.com/open-austin/Civic_Project/issues).

See the [template file](projects/00TEMPLATE.yml.example) for the expected
format of a project description.

See the [Schema.md](Schema.md) file for a description of the
project fields.

## pub Directory

Contains documents produced from the project descriptions.

* cfapi.csv - A data feed in the CFAPI format.
* projects.htincl - An HTML fragment that can be included in a web page.

Requirements are a recent a _ruby_ interpreter and the _bundler_ gem.

To setup, run:

    bundle install

To generate the documents, run:

    rake

## Data Feed

The offical data feed, produced by this project, is hosted at http://data.open-austin.org/Civic_Project/

We encourage republication and distribution of this information.

Summary description for the data feed:

> Projects developed by the community and published by Open Austin (http://www.open-austin.org), a volunteer community group that develops civic applications and tools for Austin residents. This list is produced by the Open Austin "Civic Project" tool, available at https://github.com/open-austin/Civic_Project
    

Ansible Role: Sufia
=========

Installs and configures [Sufia](https://github.com/projecthydra/sufia/); an open-source, Hydra-powered repository front-end.

WIP Notice
----------

This role is a Work-In-Progress. It is limited in the following ways:

* Under active development
* Creates a new Sufia-based site. Does not yet install an existing site from source-control.
* Only tested within very few OSes/versions

Requirements
------------

The following systems must be available for Sufia to function:
* [Solr](https://lucene.apache.org/solr/)
* [Fedora Commons](https://www.fedora-commons.org/) repository
* a SQL database (Postgres, MySQL, or SQLite)
* [Redis](https://redis.io/) key-value store

See also Dependencies below, for components that must be present on the Sufia server

Role Variables
--------------

TBD

Dependencies
------------

* [Ruby](https://www.ruby-lang.org)
* [ImageMagick](https://imagemagick.org/)
* [FITS](https://projects.iq.harvard.edu/fits)
* [LibreOffice](https://www.libreoffice.org/)

Example Playbook

    - hosts: servers
      roles:
         - { role: sufia }

License
-------

CC0

Author Information
------------------

Drew Heles

# DBLP Playground

This repo contains some code for converting the DBLP XML dump into a PostgreSQL database, and some sample queries that can be run on this database, including those that generated the tables [here](https://johnwickerson.github.io/dblp-playground/).

## Getting started

Note: I've only tested this on my Mac. I think PostgreSQL tends to be configured a little differently on Linux.

0. System requirements: PostgreSQL (`brew install postgresql`), wget (`brew install wget`), GNU's sed (`brew install gnu-sed`).

1. Start your PostgreSQL server using `pg_ctl -D /opt/homebrew/var/postgres start`. There are further instructions about getting started with PostgreSQL on [this webpage](https://www.robinwieruch.de/postgres-sql-macos-setup).

2. Run `make`. This downloads the DBLP XML dump from `http://dblp.org/xml/dblp.xml.gz`, unzips it into `dblp.xml`, and then converts it into a PostgreSQL database. Caution: the DBLP XML dump is quite a large file, and converting it into a database took me about half an hour.

3. Run `make myqueries`. See the Makefile for the gory details.

## Credits

My code is adapted from some code I found on [this website](http://agdb.informatik.uni-bremen.de/dblp/statistics.php). Unfortunately I can't find any names of people to credit. My SQL queries are hodge-podge of snippets pasted from StackOverflow.

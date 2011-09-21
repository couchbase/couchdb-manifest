# Building With Repo

## Get Repo

Get the latest version from [the google project
page](http://code.google.com/p/git-repo/downloads/list).

## Clone the Manifest

    $ mkdir couchdb
    $ cd couchdb
    $ repo init -u git@github.com:couchbase/couchdb-manifest.git
    $ repo sync

or, for the new and exciting preview branch:

    $ mkdir couchdb
    $ cd couchdb
    $ repo init -u git@github.com:couchbase/couchdb-manifest.git -m branch-preview.xml
    $ repo sync

## Build

    $ rake

# Building With Repo

## Get Repo

    $ curl http://android.git.kernel.org/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo

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

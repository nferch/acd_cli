TODO
----

General / API
~~~~~~~~~~~~~

* switch to multiprocessing (?)
* metalink support (?)

API
~~~

* support of node labels
* support for assets (?)
* favorite support (feature not yet announced officially)
* rip out the Appspot authentication handler

CLI
~~~

* unify the find action
* check symlink behavior for different Python versions (#95)

FUSE
~~~~

* invalidate chunks of StreamedResponseCache (implement a time-out)
* respect flags when opening files
* implement flush
* use a filesystem test suite

File Transfer
~~~~~~~~~~~~~

* more sophisticated progress handler that supports offsets
* copy local mtime on upload (#58)
* add path exclusion by argument for download
* piped overwrite

User experience
~~~~~~~~~~~~~~~

* shell completion for remote directories
* even nicer help formatting
* log coloring

Tests
~~~~~

* cache methods
* more functional tests
* fuse module

Documentation
~~~~~~~~~~~~~

* write how-to on packaging plugins (sample setup.py)


couchbeam 0.4.3 - 2009-2010 (c) Benoît Chesneau <benoitc@e-engura.org>
---------------------------------------------------------------

**couchbeam** is a simple erlang CouchDB framework. couchbeam provides you a full featured and easy client to access and manage multiple couchdb Nodes.

Couchbeam is under Apache License 2. see LICENSE file for more details.

Full documentation of the project is on this [url](http://benoitc.github.com/couchbeam).



requirements
------------
* Erlang/OTP R12-B or newer (compiler to build, kernel,stdlib,ssl,crypto to run)
* GNU Make (might actually build with some other make as well)

installation
------------
To bulid the application simply run 'make'. This should build .beam, .app
files and documentation.

To run tests run 'make test'.
To generate doc, run 'make docs'.
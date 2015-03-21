# SCON: Java SPARQL Connectivity API

The purpose of this library is to provide a SPARQL API in a framework that will appear familiar to users of JDBC.

SCON uses HTTP for communication, and XML as the default data serialization. Much of the protocol code is
boilerplate to avoid communicating with HTTP, and parsers for converting results into ResultSet objects.
The code for this is all to be found in org.mulgara.jsparqlc. All the classes you need to access for SCON
are to be found in this package.

Because data being returned represents RDF, the library also makes heavy use of the
[MRG API](https://github.com/quoll/mrg). This is a complete Graph API for programmatic handling of RDF data,
and is developed in conjunction with this project.

Originally hosted at [Google Code](https://code.google.com/p/scon/).

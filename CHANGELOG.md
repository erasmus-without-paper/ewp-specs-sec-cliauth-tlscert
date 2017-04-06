Release notes
=============

This document describes all the changes made to the *Authenticating Clients
with TLS Certificate* document, starting from its first released version.


1.1.0
-----

* Added the `security-entries.xsd` file. It contains the definition of an XML
  element which can be used to reference the method of authentication described
  in this document. See [this
  issue](https://github.com/erasmus-without-paper/ewp-specs-sec-intro/issues/1).


1.0.1
-----

* Added a *Status* section with the information about the upcoming deprecation.
* Added a note describing what the `X-EWP-KeyId` header is
  ([why?](https://github.com/erasmus-without-paper/ewp-specs-sec-cliauth-tlscert/issues/1)).


1.0.0
-----

This document was created as a result of splitting the Architecture and
Security document into a number of separate smaller documents. This document
was already stable (version 1.7.0) before it has been split, and the "meaning"
of this "child" document has not been modified much, so we made it stable
(1.0.0) immediately.

It's worth noting however, that - while the *meaning* remained the same - the
*wording* changed substantially, to accommodate the terms introduced by the
new multiple authentication and encryption methods.

=============================================================
URL Shortening - API to generate short urls at ref.scielo.org
=============================================================

Current version: API v1
-----------------------

URL Shortening
~~~~~~~~~~~~~~

Request::

  GET /api/v1/shorten

Parameters:

  **url**
    *String* of the URL to be shortened.

Optional Parameters:

  **callback**
    *String* of the callback identifier to be returned when
    using JSONP.


Example Request::

  $ curl -X GET ref.scielo.org/api/v1/shorten?url=http://www.scielo.org

Example Response::

  "http://ref.scielo.org/rjnnhd"

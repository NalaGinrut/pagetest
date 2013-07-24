((title . "mmr"))
Artanis
=========

Artanis aims to be a very lightweight web framework for Scheme which is written all with GNU Guile.

## Features:

* very lightweight: the core artanis.scm almost 300 lines, easy to hack
and learn for newbies.
* a relative complete web-server implementation, include error page
throw and all the HTTP method (you have to specify your own handler)
* 10K concurrent performance for the server, takes advantage of the
Guile inner server. It's enough for you own site/blog.
* sinatra like style route, that's why it names "artanis" ;-)
* Database support (now use guile-dbi), mysql/sqlite/postgresql. But it's
easy to port to other database binding. (but I like dbi)
* session support
* HTML template of SXML (very easy to use for Lisper)

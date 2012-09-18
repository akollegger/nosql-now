NoSQL Now! 2012
===============

A Neo4j demonstration website to accompany a lunch &amp; learn session.

[NoSQL Now](http://nosql-now.herokuapp.com) is a one-page
website with getting started information for user who are new to Neo4j.

The hosting `web.rb` application also provides a simple proxy to a live
[Neo4j Database](http://nosql-now.herokuapp.com/webadmin).

Database Initialization
-----------------------

The database has been initialized with a simple ruby script which
populates a local Neo4j server. Ther resulting database was then
packaged and uploaded to the Neo4j Add-on as a restored backup.

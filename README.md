# Rampart Metasearch Demo

A demo metasearch that grabs and organizes results from
Google, Ask, Duckduckgo and Bing.

The metasearch is solely for demonstrating some features in
[rampart](https://github.com/aflin/rampart).  For many many reasons,
you should not use this in production.

There are two versions: One that extracts text using regular
expressions from the ``rampart-sql`` module and one that
parses html using the ``rampart-html`` module.

To start: 

``cd web_server``

and then:

``./start_metasearch_web_server.sh``

Enjoy!

Remember to do a : heroku reset -a <YOURBUILDSERVERNAME>
before every build e.g.

heroku reset -a <YOURBUILDSERVERNAME> && ./package_libmemcached 1.0.17

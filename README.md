# indexer
Golang program to index liturgical websites

Creates the following indexes:

- /dcs/public/dcs/booksindex.html
- /dcs/public/dcs/servicesindex.html

And, for each year/month/day, creates day indexes in:

- /dcs/public/dcs/indexes

The booksindex.html file an index of:

- /dcs/public/dcs/h/b
- /dcs/public/dcs/p/b

The servicesindex.html file an index of:

- /dcs/public/dcs/h/s
- /dcs/public/dcs/p/s

where, 
- /h/ = html
- /p/ = pdf

Note: the code in this repository will be merged into Doxa and this repository will then be deleted.

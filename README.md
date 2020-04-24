# jbackup: lj/dw journal download tool



`jbackup` was obtained from 
https://github.com/dreamwidth/dw-free/blob/master/src/jbackup/jbackup.pl 

In its original state it is a single file in the
https://github.com/dreamwidth/dw-free/ repository, and was last edited in
2013, (commit 9ac1042) when it was imported from lj.  It requires the
`libxmlrpc-lite-perl` and `libterm-readkey-perl` packages.  The plan is to
make it import in a format compatible with whatever my current blog archive
format is or may become.

See (Chapter 29. Exporting
Comments)[https://www.livejournal.com/doc/server/ljp.csp.export_comments.html]
for details about how comments are read.  Since this is an LJ document, it's
not clear how to map references to OpenID users into their usernames.  If
necessary, they can be scraped from attributes and hidden fields in
https://www.dreamwidth.org/manage/circle/edit

# proj2-flask
A starter project for using the Flask framework

## Author: Megan McMillan

# Address on ix

http://ix.cs.uoregon.edu/~mcmillan/htbin/cis399/proj2-flask/

## In your workspace

Copy CONFIG.base.py to CONFIG.py, and edit it. You can probably use
the standard port 5000 if you are the only user of the computer.
On ix, you should generate a random port number; numbers between
4000 and 8000 are good.  (Numbers below 1000 are not permitted;
those are 'privileged'

type `make install`

You might have to edit the Makefile to find the right version of
pyvenv.  The Makefile has a hacky workaround for a bug in the ubuntu
version on ix.cs.uoregon.edu; I think this will still work in most
environments, although it will be slower.  Try it and let me know.

If you can run flask applications in your development environment, the
application would might be run by
`   python3 syllabus.py`
and then reached with url
`   http://localhost:5000`

Note that we do not use app.cgi when we can run flask applications
directly.

This should work on MacOS, or on your own Linux box if you have one. I
don't know about Windows.  It won't work this way on ix:
There is only one port 5000 on ix, and we can't
all share it.

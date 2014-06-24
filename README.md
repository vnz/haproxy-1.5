Build haproxy package
=====================

* debian/rules clean
* git-buildpackage -i -us -uc -b


Upstream update
===============

* git-import-orig path/to/haproxy\_1.5.1.orig.tar.gz
* dch -v "1:1.5.1-1" -M -D unstable "Upstream release haproxy 1.5.1"
* commit now
* git tag 1.5.1-1



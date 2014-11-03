Build haproxy package
=====================

* debian/rules clean
* git-buildpackage -i -us -uc -b


Upstream update
===============

* debian/rules clean
* git-import-orig path/to/haproxy\_1.5.x.orig.tar.gz
* dch -v '1:1.5.x-1' -M -D unstable 'Upstream release haproxy 1.5.x'
* git add .
* git commit -m 'Upstream release haproxy 1.5.x'
* git tag 1.5.x-1



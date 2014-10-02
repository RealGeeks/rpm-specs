# Real Geeks Python RPM Specs

Based on the SCL repository here, but with upgraded versions:

http://people.redhat.com/bkabrda/python27-rhel-6/

Support script stolen from here:

https://github.com/LukeCarrier/rpm-specs


## How to build

```
cd ~/rpmbuild
SUPPORT/auto-build.sh -s SPECS/some-package-version.spec
```

Hopefully, the package will build as it should and you'll end up with a working package you can install like so:

```
rpm -i ../RPMS/$(arch)/some-package-version.rpm
```

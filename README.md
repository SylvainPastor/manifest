Manifest collections
=======================

### Getting Repo

1. Get the repo tool ```git clone https://gerrit.googlesource.com/git-repo```
1. Put git-repo/repo into your $PATH

### Getting Raspberry Pi

1. Create a directory for odroid development ```mkdir pi && cd pi```
1. Perform a clone of the relevant projects using repo ```repo init -u "https://github.com/SylvainPastor/manifest.git" -m raspberrypi_yocto.xml && repo sync```

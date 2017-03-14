## NEMS Platform Instructions

To incorporate the NEMS platform into your subsite project you need to
copy the file `resources/composer/scripts/post-install-cmd/install-nems-platform`
to the same location into your subsite project. Make sure that this
file is executable.

This script will:
- install the nems platform source code into your projects `lib/` directory.
- it will add an include line into your site.make for its contributed modules.
- it will add a .gitignore file to your lib folder to exclude its source code.

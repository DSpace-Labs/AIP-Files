# AIP-Files

Repo of re-usable AIP files for DSpace testing

## What to include
Any resources added to this repository should be freely distributable.  Material under copyright should not be included.

## Sample Datasets

- DogPhotosAIP.zip : a set of small image files of a dog
- dogAndReport.zip : the contents of DogPhotosAIP.zip plus sample data featured in the following tutorial
  - https://github.com/terrywbrady/restReportTutorial

## To create test data

    cd /tmp
    mkdir aipout
    cd aipout
    dspace packager -d -a -i 123456789/0 -e test@test.edu SITE.zip
    zip -cf AIP.zip *.zip

## Other Datasets

- SQL Load for DSpace Entities
  - https://www.dropbox.com/s/xh3ack0vg0922p2/configurable-entities-2019-05-08.sql?dl=1
- Assetstore
  - https://www.dropbox.com/s/zv7lj8j2lp3egjs/assetstore.tar.gz?dl=1

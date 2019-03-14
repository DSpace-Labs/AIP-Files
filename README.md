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
  - https://www.dropbox.com/s/ovqp394y3vofnwa/entities7-test-db.sql.gz?dl=1

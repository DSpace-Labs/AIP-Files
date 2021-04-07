# AIP-Files

Repo of re-usable AIP files / Sample Data for DSpace testing

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

- **Sample DSpace Entities** - Provides sample configurable entities data, including sample Journals, Volumes, Issues, Publications, Persons and OrgUnits.
  - See the [`demo-entities-data`](https://github.com/DSpace-Labs/AIP-Files/releases/tag/demo-entities-data) tag/release in this repository for details/instructions.
- **Demo Site AIPs** - Provides the default demo content used on http://demo.dspace.org
  - See the [`demo-site-aips`](https://github.com/DSpace-Labs/AIP-Files/releases/tag/demo-site-aips) tag/release in this repository for details/instructions.

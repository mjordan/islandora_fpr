# Islandora FPR

## Overview

This is a proof-of-concept module to retrieve and parse the [Archivematica Format Policy Registry](https://ww.archivematica.org/en/docs/archivematica-1.3/user-manual/preservation/preservation-planning/#fpr) (FPR) entry for a [PRONOM PUID](http://en.wikipedia.org/wiki/PRONOM), which the module parses from the FITS datastream accompanying an Islandora object, if that datastream is available.

Currently, the FPR entry retrieved is the one that describes how to generate access deriviates for the OBJ datastream of an object.

## Dependencies

[Islandora FITS](https://github.com/Islandora/islandora_fits)

## Configuration

To configure the URL of the Archivematica FPR endpoint, visit admin/islandora/tools/fpr.

## Usage

Currently, visiting islandora/object/%islandora_object/fpr will fetch FPR entries describing how to create access and preservation derivatives for the object's OBJ datastream and print it out to the user.

## Maintainer

* [Mark Jordan](https://github.com/mjordan)


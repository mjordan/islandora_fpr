# Islandora FPR

## Overview

This is a proof-of-concept module to retrieve and display selected [Archivematica Format Policy Registry](https://ww.archivematica.org/en/docs/archivematica-1.3/user-manual/preservation/preservation-planning/#fpr) (FPR) entries corresponding to a [PRONOM PUID](http://en.wikipedia.org/wiki/PRONOM), which the module parses from the FITS datastream accompanying an Islandora object, if that datastream is available.

Currently, the module retrieves the FPR entries for commands that create access and preservation derivatives from an object's OBJ datastream if the object has a FITS datastream.

## Dependencies

[Islandora FITS](https://github.com/Islandora/islandora_fits)

## Configuration

To configure the URL of the Archivematica FPR endpoint, visit admin/islandora/tools/fpr.

## Usage

This module inserts a "FPR" tab into each object's display. Clicking on this tab reveals the commands.

## Maintainer

* [Mark Jordan](https://github.com/mjordan)


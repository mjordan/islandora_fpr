# Islandora FPR Image

## Overview

This sample module creates a derivative from a JPEG OBJ file with DSID 'FPR_IMAGE_TEST' by running the access command defined for JPEGs in the FPR. It is a sample module illustrating how an FPR command can be used to create a derivative.

## Dependencies

[Islandora FPR](https://github.com/mjordan/islandora_fpr)

## Configuration

None.

## Usage

To see this module in action, you need to "Regenerate all derivatives" (under an object's "Properties" tab). The following conditions must be in place:

*The object's OBJ datastream must have a Mimetype of "image/jpeg"
*The object must have an FPR_ACCESS_CMD datastream


## Maintainer

* [Mark Jordan](https://github.com/mjordan)


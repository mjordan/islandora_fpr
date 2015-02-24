# Islandora FPR Image

## Overview

This sample module creates a derivative from a JPEG OBJ file with DSID 'FPR_IMAGE_TEST_DS' by running the access command defined for JPEGs in the FPR. It is a sample module illustrating how an FPR command can be used to create a derivative.

![Datastreams added by the FPR modules](https://dl.dropboxusercontent.com/u/1015702/linked_to/islandora_fpr/islandora_fpr_sample_derivative.jpg)

## Dependencies

[Islandora FPR](https://github.com/mjordan/islandora_fpr)

## Configuration

None. It only needs to be enabled.

## Usage

This module has only been tested on objects that have an OBJ datastream with the mimetype "image/jpeg". To see the module in action, you need to "Regenerate all derivatives" (under an object's "Properties" tab). The following conditions must be in place:

* The object's OBJ datastream must have a Mimetype of "image/jpeg"
* The object must have an FPR_ACCESS_CMD datastream. Currently, this is generated when someone clicks on the "FPR" tab for the object. So, you must click on the "FPR" tab for any objects that you want this module to generate a derivative for before the module will generate it.


## Maintainer

* [Mark Jordan](https://github.com/mjordan)


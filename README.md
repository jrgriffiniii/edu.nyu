# NYU Libraries GeoBlacklight Metadata Repository

This repository is the most current source for geospatial metadata housed within the NYU Libraries collection, the [Spatial Data Repository](geo.nyu.edu). We encourage any institution to index our metadadata into their own discovery environment(s).

#### Metadata validation checks

Our metadata is validated to be in compliance with the current [GeoBlacklight 1.0 schema](https://github.com/geoblacklight/geoblacklight/blob/master/schema/geoblacklight-schema.md) through Travis-CI. Click the "build-failing" button below to see which of our records (if any) have validation errors.

[![Build Status](https://api.travis-ci.org/OpenGeoMetadata/edu.nyu.svg?branch=master)](https://travis-ci.org/OpenGeoMetadata/edu.nyu)

#### Contribution and enhancement status

![Open for metadata contributions](https://upload.wikimedia.org/wikipedia/commons/archive/0/0e/20170421060213%21Location_dot_green.svg) *Open for metadata contributions and enhancements*

#### Suggested enhancements our existing metadata

There are manny potential ways members of the GeoBlacklight community can enhance our metadata. Some examples include (but are not limited to):
* Fixing typos
* Normalizing string values for subjects and placenames
* Adding placename strings to records
* Enhancing descriptions
* Correcting errors on bounding box values
* Suggesting references for contextual information
* Submitting fixes for invalid records

#### Preferred process for submitting enhancements

We prefer that enhancements be consolidated into as few branches as possible. Here is a suggested workflow:
* Clone our entire repository to your desktop
* Save all new or updated files according to our naming convention
* Create a branch that names and describes the nature of your fixes. If the scope of the changes is large, you may want to create an issue to describe your intended work
* Submit a pull request
* Assign the review task to Andrew Battista or Taylor Hixson

#### Contact Information

If you have any questions about remediating this metadata or would like to discuss larger-scale remediation projects, please reach out to Andrew Battista or Taylor Hixson or create an issue within this repository.

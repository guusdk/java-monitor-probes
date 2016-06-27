[![Build Status](https://travis-ci.org/guusdk/java-monitor-probes.svg?branch=master)](https://travis-ci.org/guusdk/java-monitor-probes)

# Java-monitor probes
This repository contains the probes for http://java-monitor.com. These probes continuously collect monitoring data from a Java process, and submit that data to the java-monitor website, where it is stored and made accessible.

## Building the source
Apache Ant is used to build this project. To build the artifacts, execute `ant package`. The artifacts will be generated in a folder named `dist`.

## Using the artifacts
**Note** The artifacts that you build locally will not upload data to java-monitor!

The java-monitor website personalizes probe, before offering it for download. The code in this repository does not contain such personalisation. The artifacts that are generated will therefor not add monitoring data to the java-monitor platform!

## Project History
The original source code was taken from http://code.google.com/archive/p/java-monitor-probes/

The repository at that location is no longer active (all that remains on that page is an archive, which was used to create this repository).

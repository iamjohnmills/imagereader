# ImageReader
A simple feed reader with image analysis and comparison.

https://iamjohnmills.github.io/imagereader/

## Features
Parses RSS and Atom feeds

Gets various image and media urls from feed and HTML sources

Analyzes and filters out irrelevant images

Compares images and filters out duplicates

Uses a proxy server ([cors-anywhere](https://github.com/iamjohnmills/cors-anywhere)) to deal with cors issues and mixed http/s media.

## Highlights
All native JS and no dependencies.

Extensive ES6 usage, including map, filter, reduce, and promises

Images are scaled down and compared for duplicate by a threshold value derived from a root mean square comparison of two image buffers.

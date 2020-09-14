# ImageReader
A simple feed reader with image analysis and comparison.

https://iamjohnmills.github.io/imagereader/

## Features
Parses RSS and Atom feeds

Gets various image and media urls from feed and HTML sources

Analyzes and filters out irrelevant images

Compares images and filters out duplicates

Note: You need a plugin to allow CORS in your browser: https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf (I would like to host my own CORS proxy server in the future for this project)

## Highlights
All native JS and no dependencies.

Extensive ES6 usage, including map, filter, reduce, and promises

Images are scaled down and compared for duplicate by a threshold value derived from a root mean square comparison of two image buffers.

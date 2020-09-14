# ImageReader
A simple feed reader with image analysis and comparison.

https://iamjohnmills.github.io/imagereader/

## Features
Parses RSS and Atom feeds

Gets various image and media urls from feed and HTML sources

Analyzes and filters out irrelevant images

Compares images and filters out duplicates

Note: I'm using this CORS proxy in the front-end part of my app: https://github.com/Rob--W/cors-anywhere/ until I can find a better way to handle this.

## Highlights
All native JS and no dependencies.

Extensive ES6 usage, including map, filter, reduce, and promises

Images are scaled down and compared for duplicate by a threshold value derived from a root mean square comparison of two image buffers.

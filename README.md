# Restaurant Review App
This project is part of Udacity's Front End Developers Nanodegree.

---

## Table of Contents

- [Specifications](#specifications)
- [Installation](#installation)

## Specifications

For this assigmement I was given a starter code of a restaurant reviews website with a map. However, this code was a mess. My job was to make it responsive, accessible and to make sure it works offline too.

For responsiveness I modified the page according to the various breakpoints of the viewports.
I made the website accessible for visually impaired by adding a tabindex (skipping over the map), a skip to content link and some ARIA definitions.
To use the website offline, the added serverworker caches all files so they are still accessible.

## Installation

Clone this repository, open up your terminal cd into the folder and run `python -m SimpleHTTPServer 8886` (or `python3 -m http.server 8886` if you have Python 3.x installed). Then in your browser go to `http://localhost:8886`. There you have it!
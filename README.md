# shotspotter-locations

Leaked data on the location of [ShotSpotter listening devices](https://www.soundthinking.com/). Based on [info from J.B Crawford](https://computer.rip/2024-03-01-listening-in-on-the-neighborhood.html).

A KML of data pulled from an [article by WIRED magazine](https://www.wired.com/story/shotspotter-secret-sensor-locations-leak/) which interestingly did not allow a very low zoom-level in their own visualization. I opened up the original [Flourish visualization iFrame](https://flo.uri.sh/visualisation/16818696/embed), and in the source code was the actual, very high-resolution lat/lon of the Shotspotter locations.

In this repo is the parsed KML file, and `shots.json` which is a JSON-formatted version of the javascript object found in the embed page.

This work is covered under [Creative Commons zero license](https://creativecommons.org/publicdomain/zero/1.0/)

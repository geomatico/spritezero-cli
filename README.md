# spritezero-cli

A command-line interface to [spritezero](https://github.com/mapbox/spritezero).

## Installation

    npm install -g @geomatico/spritezero-cli

## Usage

    spritezero [output filename] [input directory]

      --retina      shorthand for --ratio=2
      --ratio=[n]   pixel ratio
      --unique      map identical images to multiple names

Spritezero reads an input directory containing SVG files and generates a JSON
layout file and PNG spritesheet.

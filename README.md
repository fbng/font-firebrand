# Font Firebrand

Font Firebrand is a set of vector icons similar to the Font Awesome icon set.  These are icons specifically designed for use in Firebrand applications.

## Requirements

Use a Docker image in a Unix environment (preferred): <https://hub.docker.com/r/telor/fontcustom-worker>.

Or install the dependencies locally: <https://github.com/FontCustom/fontcustom#installation>.

## Project Setup

To add an icon to the set:

1. Save the SVG in the vectors folder.
2. From the command line in the Font-Firebrand project root, using docker, run:

`docker run -it -v $(pwd):/app/project telor/fontcustom-worker fontcustom compile`

or for a local installation run: `fontcustom compile`

## Testing

Open `Font-Firebrand/fonts/font-firebrand-preview.html` in a browser to see the compiled results.

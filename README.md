# Tiler

## Intro

Command line tool for splitting large images into tiles.

## Usage

`tiler [<flags>] <input> [<output>]`

```
Flags:
      --help          Show context-sensitive help (also try --help-long and --help-man).
  -v, --verbose       Verbose mode.
  -w  --width=16      Tile width (default 16).
  -h  --height=16     Tile height (default 16).
  -f, --format="png"  Image output format.

Args:
  <input>     Input image file path (accepted jpeg, png).
  [<output>]  Output directory. Defaults to the current directory
  ````

# gv2map

Converter from graphviz to PNG/SVG map. Wrapper of neato, gvmap and sfdp. Automatically detects output format (from second argument extension).

## Install

```
wget link -O ~/bin/
chmod a+x ~/bin/gv2map
```

or, if you don't want to add `~/bin/` to your `$PATH`:

```
sudo wget link -O /usr/local/bin/
sudo chmod a+x /usr/local/bin/
```

## Usage

```
gv2map <input> <output>
```

## Examples

```
gv2map graph.gv map.png
gv2map graph.gv map.svg
```

# Rust binding for GRASS GIS libraries

Rust bindings of [GRASS GIS](https://grass.osgeo.org/) libraries.
To generate the bindings execute:

```bash
CPATH=:/lib:$GISBASE/include OUT_DIR=binding cargo build
```

Where `GISBASE` is an environmental variable with the path to the directory containing
the compiled GRASS GIS libraries and tools.

This code is released under the [GPLv3](./LICENSE).

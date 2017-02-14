# Rust binding for GRASS GIS libraries

[GRASS GIS](https://grass.osgeo.org/) to generate the bindings execute:

```bash
CPATH=:/lib:$GISBASE/include OUT_DIR=binding cargo build
```

Where `GISBASE` is a environmental variable with the compiled GRASS GIS libraries and executables.

This code is released under the [GPLv3](./LICENSE).

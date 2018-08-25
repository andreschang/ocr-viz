# OCR Viz
OCR Viz extends the visual and creative capabilities of OCR Tools with custom colormapping and soon-to-be-added filtering tools.

## Installing / Getting started

OCR Viz runs in Python, and it requires a few basic packages: [Matplotlib](https://matplotlib.org/), [Basemap](https://matplotlib.org/basemap/), [SciPy](https://www.scipy.org/), and [NetCDF4](http://unidata.github.io/netcdf4-python/). The packages can be installed individually using the [Anaconda Navigator](https://www.anaconda.com/distribution/) or [Canopy](https://www.enthought.com/product/canopy/) desktop applications (no command line needed). 

Conda users may also set up their environment through the command line by typing

```shell
conda env create -f environment.yml
```

and then switching to the new environment by typing ```source activate ocrtools``` (Mac) or ```activate ocrtools``` (Windows).

Once your environment is ready, start exploring ```demo.py```.  The ```ocrtools``` folder is preloaded with a ```data``` directory and sample climate data, so it should run out of the box.

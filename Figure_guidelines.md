Figures:
- cmocean
- averaging time of 1 year
- panel label top left corner a
- ordering L to R, top to bottom
```
a  b    c    d
e   f   g    h

```
- alphabetical order of models
- aspect ratio of x and y equal
- colour lines - Chris (12 models)
```
#12 model colours for 12 models, generated using https://colorbrewer2.org/#type=qualitative&scheme=Paired&n=12
modelcolours=['#a6cee3','#1f78b4','#b2df8a','#33a02c','#fb9a99','#e31a1c','#fdbf6f','#ff7f00','#cab2d6','#6a3d9a','#ffff99','#b15928']
```
- Ocean1 and 2 (replace Ocean 0 with end of Ocean1)
- 

Conda package:

Install miniforge3: https://github.com/conda-forge/miniforge?tab=readme-ov-file#miniforge3

```
conda config --add channels conda-forge
conda config --set channel_priority true
conda create -y -n isomip_plus jupyter xarray netcdf4 numpy scipy matplotlib cftime cmocean
conda activate isomip_plus
jupyter notebook
```

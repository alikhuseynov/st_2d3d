### Visualizing gene expression topography in 2D and 3D.
#### Exploring ACE2 and NRP1 expression patterns on healthy human heart left ventricle (publicly available 10X Visium data).

ACE2 transcript encodes for SARS-CoV2 receptor on host cells, and NRP1 encodes for a host protein potentiating SARS-CoV-2 infectivity.

![gene expression topography](https://github.com/alikhuseynov/st_2d3d/blob/main/st_coexp.001.jpeg)

- 1st-2nd row: visualizing expression per gene, co-expression spots of ACE2+ and NRP1+
- 3rd row: mean co-expression of ACE2+ and NRP1+

[Rmd script](https://github.com/alikhuseynov/st_2d3d/blob/main/st_heart_coexp.Rmd) using [Seurat](https://github.com/satijalab/seurat), [Plotly](https://github.com/plotly), [Fields](https://github.com/NCAR/Fields), [spatstat](https://github.com/spatstat/spatstat), and other cool packages.

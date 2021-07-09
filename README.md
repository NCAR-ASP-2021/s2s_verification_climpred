# S2S Forecast verification with `climpred`

This notebook is part of the [tutorials](https://www.cgd.ucar.edu/events/2021/asp-colloquia/tutorials.html) in the [ASP summer school](https://www.cgd.ucar.edu/events/2021/asp-colloquia/).

In the [S2S verification tutorial](https://docs.google.com/document/d/1nQOyjjAjdqN2sl3IeJYCytCo4l_49GW6fMgkKjsnsCc/edit),
we use `climpred` https://climpred.readthedocs.io/en/stable/ to verify subseasonal-to-seasonal (S2S) forecasts against observations.


# Environment

It is recommented to use the enviroment `add_name` on `NCAR_casper`.

Else create your own environment:

```bash
  conda activate
  conda env create -f s2s-climpred.yaml
  # update existing
  # conda env update -f s2s-climpred.yaml
  conda activate s2s-climpred
```


# Other resources

- `xarray`: working horse for geospatial data in python
    - documentation: xarray.pydata.org/
    - tutorial: https://xarray-contrib.github.io/xarray-tutorial/
- `xskillscore`: is built on top of `xarray` and provides `metric`s to `climpred`
    - documentation: https://xskillscore.readthedocs.io/en/stable/
    - quick-start: https://mybinder.org/v2/gh/xarray-contrib/xskillscore/master?urlpath=lab
- `climpred`:
    - documentation: https://climpred.readthedocs.io/en/stable/
    - data model: https://climpred.readthedocs.io/en/stable/setting-up-data.html
    - classes: https://climpred.readthedocs.io/en/stable/prediction-ensemble-object.html
    - list of initialized public datasets to work with: https://climpred.readthedocs.io/en/stable/initialized-datasets.html
    - terminology: https://climpred.readthedocs.io/en/stable/terminology.html
    
--- 

# Usage questions

Consider...

- raising an [issue](https://github.com/pangeo-data/climpred/issues), which can be transferred to [discussions](https://github.com/pangeo-data/climpred/discussions)
- reaching out on [slack](asp2021-s2s.slack.com)

# Tutorial leads

- Aaron Spring
- Judith Berner
- Abby Jaye

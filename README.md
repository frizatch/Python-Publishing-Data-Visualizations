# Publishing with Python
An introduction to using data visualization libraries for creating your figures

There are many different libraries one can use for data visualization in python. They all have different strengths and weaknesses. In this workshop, we'll examine creating visuals by relying on two libraries: *maplotlib* and *seaborn*, but be aware there are others that may fit your purposes better.

In addition to the plotting libraries we'll examine, we'll also introduce *numpy* and *pandas*, two libraries essential for organizing data to be easily examined and displayed.

## Workshop Goals

By the end of this workshop, you'll:

- Be familiar with the python visualization libraries *matplotlib* and *seaborn*
- Have exposure to the libraries *numpy*, *pandas* and *geopandas* for working with data
- Know how to use python for creating figures to add to reports and paper submissions

## Data Visualization Libraries
Here is a brief table highlighting a few and why you may want to use them:

| Library | Description | Pros | Cons | Interactivity | Strength | Export formats |
| ------- | ----------- | ---- | ---- | ------------- | -------- | -------------- |
| Matplotlib | low-level library | versatile | refining graphic is complex | no | can plot anything | PNGs SVGs |
| Seaborn | high-level | minimal code for high-level graphics | | no |
| Plotly | |  |  | yes | |
| Bokeh |  | |  | yes | |
| Folium |  | display data on Leaflet maps|
| Geoplotlib | | | output is temporary interactive window and only option to save .png | yes |

Here are the ones we'll focus on:

[Matplotlib](https://matplotlib.org/)

You can see the [common plot types](https://matplotlib.org/stable/plot_types/index.html) available for matplotlib. The [gallery page](https://matplotlib.org/stable/gallery/index.html) for matplotlib has many examples of full figures with available source codes for their creation.

<p align="center">
<img src="images/figureanatomy.jpg" width="300"/>
</p>

Note that pandas.DataFrame.plot is a convenient wrapper around Matplotlib to create simple plots.

[Seaborn](https://seaborn.pydata.org/)

Plotly

Folium

Geoplotlib

Altair?




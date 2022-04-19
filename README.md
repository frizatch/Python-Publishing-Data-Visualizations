# Publishing with Python      <img src="images/PyLogo.png" width="75"/>  ---->   <img src="images/smokerregression.png" width="100"/>
An introduction to using data visualization libraries for creating your figures

There are many different libraries one can use for data visualization in python. They all have different strengths and weaknesses. In this workshop, we'll examine creating visuals by relying on two libraries: *maplotlib* and *seaborn*, but be aware there are others that may fit your purposes better.

In addition to the plotting libraries we'll examine, we'll also introduce *numpy* and *pandas*, two packages essential for organizing data to be easily examined and displayed.

## Workshop Goals

By the end of this workshop, you'll:

- Be familiar with the python visualization libraries *matplotlib* and *seaborn* and how they work
- Have exposure to the libraries *numpy*, *pandas* and *geopandas* for working with data
- Know how to use python for creating figures to add to reports, posters and papers

## Workshop Resources

- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/)
- [Seaborn User Guide](https://seaborn.pydata.org/tutorial.html)
- [NumPy Documentation](https://numpy.org/doc/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [GeoPandas Documentation](https://geopandas.org/en/stable/docs.html)
- You can find datasets we'll use in this [data folder](https://www.dropbox.com/sh/wk6t92vp4l4cq53/AAAFzaD07V2LyKdhAjO54tefa?dl=0) on Dropbox
- Other similar Airbnb data can be found on the [Inside Airbnb website](http://insideairbnb.com/get-the-data/)
- [Jupyter Notebook](https://mybinder.org/v2/gh/frizatch/Python-Publishing-Data-Visualizations.git/main?labpath=PublishingWithPython.ipynb) of examples accessed via Binder

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

Matplotlib also supplies these amazing [cheetsheets](https://matplotlib.org/cheatsheets/) and other handouts on their website. I'm mainly including them here to give a visual sense of all that can be accomplished with this library:

<p align="center">
<img src="images/matplotlib_cheatsheets-1.jpg" width="700"/>
</p>

<p align="center">
<img src="images/matplotlib_cheatsheets-2.jpg" width="700"/>
</p>


<p align="center">
<img src="images/figureanatomy.jpg" width="500"/>
</p>

There is detailed information and examples on styling figures on matplotlib's [Introductory Usage Guide](https://matplotlib.org/stable/tutorials/introductory/usage.html), but we'll go over some of these in our notebook.

Note that pandas.DataFrame.plot is a convenient wrapper around Matplotlib to create simple plots.

[Seaborn](https://seaborn.pydata.org/)

Plotly

Folium

Geoplotlib

Altair?




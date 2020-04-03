## Usage

Simple plots in a Jupyter notebook of COVID-19 data without analysis. 


A country can be plotted with

```
plot_country("Germany", cases, deaths, startday=40, log=True)
plot_country("US", cases, deaths, startday=0, log=False)
```

where Germany will be plotted with a logarithmic y-axis and the US not. The startday indicates the starting date of the x-axis.

## Credits

* Thanks to Vincents [code for extraction of the data](https://github.com/VincentStimper/COVID-19-modeling)
* Thanks to the [dataset of Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19)

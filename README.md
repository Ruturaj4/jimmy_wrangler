Jimmy Wrangler
==============================

Data Explorer : Traveling the world on a mission to discover new data

Author: Ruturaj Kiran Vaidya

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

### Before Getting Stated

If you are only interested in looking at the notebook then go to (There are notebook rendering problems in github ecosystem, in particularly with plotly):

https://nbviewer.jupyter.org/github/Ruturaj4/jimmy_wrangler/blob/master/notebooks/1.0-rkv-Jimmy-Wrangler.ipynb

Also, all the values are estimates and from 2018 United States census and homelessness estimated data. All the graphs are plotted using `plotly`.

### Aim

Jimmy Wrangler - Data Explorer is an introductory data science project. The objectives of this project are:

* Find public data sets
* Do exploratory data analysis by combining them
* Plot results

### Project Idea

Homelessness count vs Total resident population - 2018, United States

### Gathering datasets

I believe that the datasets we use for analysis must come from credible sources.
Hence, for this project I used data from United States government. I used 
a couple of datasets - homelessness dataset and US census dataset.

Dataset source:

* Homelessness data: https://www.hudexchange.info/resources/documents/2007-2018-PIT-Counts-by-CoC.xlsx
* United States census estimate data - https://www2.census.gov/programs-surveys/popest/tables/2010-2018/state/totals/nst-est2018-01.xlsx

### Plots

1) Following plot shows an estimated percentage of homelessness in 2018 by state.

100 * Homeless Count / Total population

![alt text](/reports/figures/homelessness_percentage.png)

2) Following plot shows an estimated count of homeless population in 2018 by state (per 10000 population). Note that the following graph is almost same as above, I though it would be better to plot realistic numbers (greater than 1).

10000 * Homeless Count / Total population

![alt text](/reports/figures/homelessness_per_10000.png)

3) Following geo-plot shows an estimated percentage of homelessness in 2018 by state.

![alt text](/reports/figures/homlessness_geoplot.png)

### License

<b>MIT</b>

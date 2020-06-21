# covid-19-visualizations
In order to view the notebook and code completely, use this [nbviewer link](https://nbviewer.jupyter.org/github/awang378/covid-19-visualizations/blob/master/Global%20Data%20Visualization%20with%20Python.ipynb) as it renders Jupyter Notebook file into a HTML page which correctly displays some of the visualizations.

## Background
The COVID-19 pandemic has had a huge impact on everyday life from social distancing to mask wearing. Out of this pandemic, there is tons of data coming out describing the situation of how its affecting people and why we need to do our part to overcome it. For example, everyday we are getting information on cases, deaths, recoveries from every country in the world as testing ramps up to treat the infected and stop the spread. 

Browsing through [Medium](https://medium.com/) and [Towards Data Science](https://towardsdatascience.com/) articles, I saw so many people trying to understand the current situation through informative pieces discussing symptoms, current events, and tips as well as data scientists and developers using technology such as machine learning, data visualization, and web development to predict and track the virus impact. I was inspired by this articles so I decided to create my own project on this pandemic. In particular, data visualization is one of my interests as it is a powerful means of aiding data driven decision making and as well as beautiful story telling.

For this project, I utilized a Jupyter Notebook which is a very popular tool for data science cleaning, modeling, analysis, and visualization. It is my favorite means of utilizing Python which is the king of data science at the moment. I used [Johns Hopkin's COVID-19 time series data](https://github.com/CSSEGISandData/COVID-19) for my datasets. I utilized Pandas to clean my data and create datasets, and then the assortment of Matplotlib, Seaborn, and Altair for data visualization. My focus wasn't too much about analysis of my data, but rather get some more experience in data cleaning and data visualization using different libraries and techniques. 

There is a lot of resources which I linked some down below, but there are so many articles on Towards Data Science, videos on Youtube, and online tutorials explaining how to work with data science so anyone with some Python experience can get into this field. For creating visualizations, many people including myself learn about the various techniques and use cases by studying example visualizations and thinking about how I can apply them to my data. 

## Setup
If you're interested in utilizing this notebook locally, download [Anaconda](https://www.anaconda.com/). Add this line to the start of the notebook.
```
!pip install wget, pandas, matplotlib, seaborn, altair
```

This [article](https://towardsdatascience.com/create-virtual-environment-using-virtualenv-and-add-it-to-jupyter-notebook-6e1bf4e03415) has a great explanation on how to utilize virutal environments with Jupyter Notebook to manage dependencies. 


## Resources
* [Data Cleaning COVID Data](https://towardsdatascience.com/covid-19-data-processing-58aaa3663f6)
* [Altair Summary](https://towardsdatascience.com/python-interactive-data-visualization-with-altair-b4c4664308f8)
* [Matplotlib Gallery](https://matplotlib.org/3.1.1/gallery/index.html)
* [Seaborn Gallery](https://seaborn.pydata.org/examples/index.html)
* [Altair Gallery](https://altair-viz.github.io/gallery/index.html)

## Gallery
![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/deathsline.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/facetline.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/sbdeaths.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/statsb.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/newcasesus.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/streamgraph.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/stackedarea.png)

![image](https://github.com/awang378/covid-19-visualizations/blob/master/images/interactive.png)

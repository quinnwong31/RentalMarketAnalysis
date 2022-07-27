# RentalMarketAnalysis

## Description

The Rental Market Analysis notebook is a sample notebook that illustrates how to create interactive visualizations using numerical and visual aggregation with hvPlot and GeoViews.  Interactive visualizations are extremely powerful because they enable the user to quickly and easily analyze areas of interest on line plots, bar charts and geospatial maps by zooming and panning.   In this example, we ingest a CSV file containing a list of San Francisco neighborhoods, along with their rental growth rate and sales price per square foot.    

## Technologies

This example uses the following technologies:

- **Jupyter** - Jupyter is a web-based interactive development environment for data science and analysis. Please see [Jupyter documentation](https://jupyter.org/) for more information.
- **pandas** - pandas is a software library written for the Python programming language for data manipulation and analysis. Please see [pandas documentation](https://pandas.pydata.org/) for more information.
- **hvPlot** - hvPlot is a library that provides engaging, interactive charts that allows users to analyze and disect data visualizations.  Please see [hvPlot documentation](https://hvplot.holoviz.org/) for more information.
- **GeoViews** - GeoViews is a Python library that makes it easy to explore and visualize geographical, meteorological, and oceanographic datasets, such as those used in weather, climate, and remote sensing research.   Please see [GeoViews documentation] (https://geoviews.org/) for more information. 



## Installation

In order to use this application, you will need to install `Jupyter`, `pandas`, `hvPlot` and `GeoViews`.   Below are the instructions for installing each required library.

### Installing Jupyter

To install Jupyter, please refer to the [Jupyter Installation Guide](https://jupyter.org/install).

### Installing pandas

To install `pandas`, please refer to the [pandas Installation Guide](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html).

### Installing hvPlot

To install `hvPlot`, please refer to the [hvPlot Installation Guide](https://pypi.org/project/hvplot/)

### Installing GeoViews

To install `GeoViews`, please refer to the [GeoViews Installation Guide](https://pypi.org/project/geoviews/)

## Usage

### Launching the Notebook

To launch the Notebook, perform the following steps:

1. Open Terminal.

![Launch_Terminal](/Images/launching_open_terminal.jpg)

2. Navigate to the location of the Notebook.
3. Enter `jupyter lab` at the Terminal prompt.

![Launch Jupyter](/Images/launching_jupyter.jpg)

4. Verify that you can access Jupyter in your browser.

![Jupyter](/Images/jupyter.jpg)

Once you have launched the notebook, you can then execute each section.

1. Calculate and Plot the Housing Units per Year
For this part of the assignment, use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart

![Calculate Plot Housing Units](/Images/calculate_plot_housing_units.jpg)


2. Calculate and Plot the Average Sale Prices per Square Foot
For this part of the assignment, use numerical and visual aggregation to calculate the average prices per square foot, and then visualize the results as a bar chart

![Calculate Plot Average Sale Prices](/Images/calculate_plot_avg_sales_prices.jpg)

3. Compare the Average Sale Prices by Neighborhood
For this part of the assignment, use interactive visualizations and widgets to explore the average sale price per square foot by neighborhood

![Compare Avg Sale Prices By Neighborhood](/Images/compare_avg_sale_prices.jpg)

4. Build an Interactive Neighborhood Map
For this part of the assignment, explore the geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews.

![Build Interactive Neighborhood Map](/Images/build_interactive_neighborhood_map.jpg)

## Contributors

This sample application was authored by:

Quinn Wong (quinn.wong@gmail.com)
LinkedIn: https://www.linkedin.com/in/quinnwong/

## License

The MIT License (MIT)

Copyright (c) 2022 Quinn Wong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

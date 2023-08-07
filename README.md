# Scatter Plot using Plotly in Python

This repository provides an example of creating an interactive scatter plot using Plotly in Python. The scatter plot showcases data from the Iris dataset, where we visualize the sepal width and sepal length for different species of flowers, allowing users to filter data based on petal width.

## Requirements

To run the code in this repository, you need the following dependencies:

- Python 3.x
- Plotly
- Dash
- Pandas

You can install the required packages using pip:

```bash
pip install plotly dash pandas
```

## Getting Started

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your_username/scatter-plot-with-plotly.git
cd scatter-plot-with-plotly
```

2. Run the application:

```bash
python app.py
```

3. Open your web browser and go to `http://127.0.0.1:8050/` to view the interactive scatter plot.

## About the Scatter Plot

The interactive scatter plot displays data from the famous Iris dataset. The dataset consists of measurements for three different species of Iris flowers: Setosa, Versicolor, and Virginica.

The scatter plot visualizes the sepal width on the x-axis and sepal length on the y-axis. Each point on the plot represents an individual flower. The points are colored based on the species, and their size corresponds to the petal length.

## Interactivity

The scatter plot offers interactivity through a range slider to filter data based on petal width. By using the range slider, users can select a specific range of petal width values, and the plot will update accordingly, displaying only the data points that fall within the chosen range.

## Data Source

The Iris dataset used in this example is part of the `plotly.express` module and is available as a built-in dataset. The data is loaded using `px.data.iris()` function, which returns a pandas DataFrame containing the Iris dataset.

If you want to use your own data, you can modify the code in `app.py` and replace `px.data.iris()` with your own DataFrame containing the required columns ('sepal_width', 'sepal_length', 'species', 'petal_length', and 'petal_width').

## Credits

This example is inspired by Plotly Express's official documentation and is provided as a reference for creating interactive scatter plots using Plotly and Dash in Python.

For more information about Plotly and Dash, please refer to the official documentation:

- [Plotly](https://plotly.com/python/)
- [Dash](https://dash.plotly.com/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
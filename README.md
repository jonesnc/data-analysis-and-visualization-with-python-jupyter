# data-analysis-and-visualization-with-python-jupyter
Materials used for my UBUG 2021 presentation: Data Analysis and Visualization with Python and Jupyter Notebook

## Install
- Requires Python and pip to be installed on your system
- `pip install jupyterlab`

To run the Jupyter Notebook software (now referred to as "Jupyter Lab"), run `jupyter-lab` in your terminal.

See [here](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) for more details on installation.

## Description
This session will be an introduction the pandas Python library and Jupyter Notebook for data analysis and visualization.

While SQL is often a great solution for data analysis, Python can also be an incredibly powerful tool for data manipulation and analysis when SQL is not a practical solution. Pandas is a popular Python library that offers a wide array of fast and powerful data analysis features, making it a viable alternative to SQL.

Juptyer Notebook is a web-based development environment that combines code and data in a single interface, making it easy to share your results. Code, visualizations, and explanatory text can be combined to make your data analysis easy to read and comprehend for audiences with varying backgrounds and familiarity.

## Note
The CSV file `course_meet.csv` is not included in this repository. The SQL that was used to construct that CSV file is included in the `course_meet.ipynb` file. Unfortunately, the PL/SQL function to calculate the `ROOM_FILL_RATE` is a function developed by SUU, so you'll need to implement your own solution for calculating the `ROOM_FILL_RATE` column.

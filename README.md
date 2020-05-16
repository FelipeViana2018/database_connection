<a href="https://bokeh.org">
  <img src="https://static.bokeh.org/logos/logotype.svg" height="60" alt="Bokeh logotype" />
</a>

# Project Title

Here you'll find the panel instruction and script to connect on databases.

<table>
<tr>
  <td>Conda</td>
  <td>
    <a href="https://docs.bokeh.org/en/latest/docs/installation.html">
    <img src="https://pyviz.org/_static/cache/bokeh_conda_downloads_badge.svg"
         alt="Conda downloads per month" />
    </a>
  </td>
</tr>

<tr>
  <td>PyPI</td>
  <td>
    <a href="https://docs.bokeh.org/en/latest/docs/installation.html">
    <img src="https://img.shields.io/pypi/dm/bokeh.svg"
         alt="PyPI downloads per month" />
    </a>
  </td>
</tr>

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need Python 3.6 or later to run bokeh. You can have multiple Python versions (2.x and 3.x) installed on the same system without problems.
```
PyYAML>=3.10
python-dateutil>=2.1
Jinja2>=2.7
numpy>=1.11.3
pillow>=4.0
packaging>=16.8
tornado>=5
typing_extensions >=3.7.4

```

### Installing

These Bokeh dependencies are best obtained via the Anaconda Python Distribution, which was designed to include robust versions of popular libraries for the Python scientific and data analysis stacks.

If you are already an Anaconda user, you can simply run the command:

```
conda install bokeh
```

or by pip

```
pip install bokeh

```

## Running the tests

Run Python shell and:

```
import bokeh

```
If it's ok! Check the version:

```
bokeh.__version__

```
## Authors

* **Felipe Viana** - *Initial work* 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
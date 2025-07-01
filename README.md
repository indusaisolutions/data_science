# Basics

This section will get you started with using Python and you'll be able
to learn more about whatever you want after studying it.

# Python

1. [What is programming?](python/what-is-programming.md)
2. [Installing Python](python/installing-python.md)
3. [Getting started with Python](python/getting-started.md)
4. [ThinkPython: The way of the program](python/the-way-of-the-program.md)
5. [Variables, Booleans and None](python/variables.md)
6. [Using functions](python/using-functions.md)
7. [Setting up an editor](python/editor-setup.md)
8. [If, else and elif](python/if.md)
9. [Handy stuff with strings](python/handy-stuff-strings.md)
10. [Lists and tuples](python/lists-and-tuples.md)
11. [Loops](python/loops.md)
12. [zip and enumerate](python/zip-and-enumerate.md)
13. [Dictionaries](python/dicts.md)
14. [Defining functions](python/defining-functions.md)
15. [Writing a larger program](python/larger-program.md)
16. [What is true?](python/what-is-true.md)
17. [Files](python/files.md)
18. [Modules](python/modules.md)
19. [Exceptions](python/exceptions.md)
20. [Classes](python/classes.md)
21. [Docstrings](python/docstrings.md)

# NumPy
0. [Learn to write a NumPy tutorial](numpy/tutorial-style-guide.md): our style guide for writing tutorials.
1. [Tutorial: Linear algebra on n-dimensional arrays](numpy/tutorial-svd.md)
2. [Tutorial: Determining Moore's Law with real data in NumPy](numpy/mooreslaw-tutorial.md)
3. [Tutorial: Saving and sharing your NumPy arrays](numpy/save-load-arrays.md)
4. [Tutorial: NumPy deep learning on MNIST from scratch](numpy/tutorial-deep-learning-on-mnist.md)
5. [Tutorial: X-ray image processing](numpy/tutorial-x-ray-image-processing.md)
6. [Tutorial: NumPy deep reinforcement learning with Pong from pixels](numpy/tutorial-deep-reinforcement-learning-with-pong-from-pixels.md)
7. [Tutorial: Masked Arrays](numpy/tutorial-ma.md)
8. [Tutorial: Static Equilibrium](numpy/tutorial-static_equilibrium.md)
9. [Tutorial: Plotting Fractals](numpy/tutorial-plotting-fractals.ipynb)
10. [Tutorial: NumPy natural language processing from scratch with a focus on ethics](numpy/tutorial-nlp-from-scratch.md)
11. [Tutorial: Analysing the impact of the lockdown on air quality in Delhi, India](numpy/tutorial-air-quality-analysis.md)

# Pandas

### What is Pandas in Python?
[![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/) is the most famous python library providing fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real world** data analysis in Python. Additionally, it has the broader goal of becoming **the most powerful and flexible open source data analysis / manipulation tool available in any language**. It is already well on its way towards this goal.

In Pandas, the data is usually utilized to support the statistical analysis in **SciPy**, plotting functions from **Matplotlib**, and machine learning algorithms in **Scikit-learn**.


## Main Features
Here are just a few of the things that pandas does well:

  - Easy handling of [**missing data**][missing-data] (represented as `NaN`) in floating point as well as non-floating point data
  - Size mutability: columns can be [**inserted and deleted**][insertion-deletion] from DataFrame and higher dimensional objects
  - Automatic and explicit [**data alignment**][alignment]: objects can be explicitly aligned to a set of labels, or the user can simply
    ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
  - Powerful, flexible [**group by**][groupby] functionality to perform split-apply-combine operations on data sets, for both aggregating
    and transforming data
  - Make it [**easy to convert**][conversion] ragged, differently-indexed data in other Python and NumPy data structures
    into DataFrame objects
  - Intelligent label-based [**slicing**][slicing], [**fancy indexing**][fancy-indexing], and [**subsetting**][subsetting] of
    large data sets
  - Intuitive [**merging**][merging] and [**joining**][joining] datasets
  - Flexible [**reshaping**][reshape] and [**pivoting**][pivot-table] of datasets
  - [**Hierarchical**][mi] labeling of axes (possible to have multiple labels per tick)
  - Robust IO tools for loading data from [**flat files**][flat-files] (CSV and delimited), [**Excel files**][excel], [**databases**][db],
    and saving/loading data from the ultrafast [**HDF5 format**][hdfstore]
  - [**Time series**][timeseries]-specific functionality: date range generation and frequency conversion, moving window statistics,
    moving window linear regressions, date shifting and lagging, etc.


   [missing-data]: https://pandas.pydata.org/pandas-docs/stable/missing_data.html#working-with-missing-data
   [insertion-deletion]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html#column-selection-addition-deletion
   [alignment]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html?highlight=alignment#intro-to-data-structures
   [groupby]: https://pandas.pydata.org/pandas-docs/stable/groupby.html#group-by-split-apply-combine
   [conversion]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe
   [slicing]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#slicing-ranges
   [fancy-indexing]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#advanced-indexing-with-ix
   [subsetting]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#boolean-indexing
   [merging]: https://pandas.pydata.org/pandas-docs/stable/merging.html#database-style-dataframe-joining-merging
   [joining]: https://pandas.pydata.org/pandas-docs/stable/merging.html#joining-on-index
   [reshape]: https://pandas.pydata.org/pandas-docs/stable/reshaping.html#reshaping-and-pivot-tables
   [pivot-table]: https://pandas.pydata.org/pandas-docs/stable/reshaping.html#pivot-tables-and-cross-tabulations
   [mi]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#hierarchical-indexing-multiindex
   [flat-files]: https://pandas.pydata.org/pandas-docs/stable/io.html#csv-text-files
   [excel]: https://pandas.pydata.org/pandas-docs/stable/io.html#excel-files
   [db]: https://pandas.pydata.org/pandas-docs/stable/io.html#sql-queries
   [hdfstore]: https://pandas.pydata.org/pandas-docs/stable/io.html#hdf5-pytables
   [timeseries]: https://pandas.pydata.org/pandas-docs/stable/timeseries.html#time-series-date-functionality


### Core Components of Pandas Data Structure
Pandas have two core data structure components, and all operations are based on those two objects. Organizing data in a particular way is known as a data structure. Here are the two pandas data structures:

* **Series**
* **DataFrame**

---

## Table of contents 📋

| **No.** | **Name** | 
| ------- | -------- | 
| 01 | **[Python_Pandas_DataFrame](pandas/001_Python_Pandas_DataFrame.ipynb)** |
|    | 1.1 **[001_Python_Pandas_DataFrame_from_Dictionary](pandas/001_Python_Pandas_Methods/001_Python_Pandas_DataFrame_from_Dictionary.ipynb)** |
|    | 1.2 **[Python_Pandas_DataFrame_from_List](pandas/001_Python_Pandas_Methods/002_Python_Pandas_DataFrame_from_List.ipynb)** |
|    | 1.3 **[Python_Pandas_DataFrame_head()_and_tail()](pandas/001_Python_Pandas_Methods/003_Python_Pandas_DataFrame_head()_and_tail().ipynb)** |
|    | 1.4 **[004_Python_Pandas_DataFrame_drop_columns](pandas/001_Python_Pandas_Methods/004_Python_Pandas_DataFrame_drop_columns.ipynb)** |
|    | 1.5 **[Python_Pandas_DataFrame_drop_duplicates](pandas/001_Python_Pandas_Methods/005_Python_Pandas_DataFrame_drop_duplicates.ipynb)** |
|    | 1.6 **[Python_Pandas_DataFrame_drop_columns_with_NA](pandas/001_Python_Pandas_Methods/006_Python_Pandas_DataFrame_drop_columns_with_NA.ipynb)** |
|    | 1.7 **[Python_Pandas_DataFrame_rename_columns](pandas/001_Python_Pandas_Methods/007_Python_Pandas_DataFrame_rename_columns.ipynb)** |
|    | 1.8 **[Python_Pandas_DataFrame_to_Python_dictionary](pandas/001_Python_Pandas_Methods/008_Python_Pandas_DataFrame_to_Python_dictionary.ipynb)** |
|    | 1.9 **[Python_Pandas_DataFrame_set_index](pandas/001_Python_Pandas_Methods/009_Python_Pandas_DataFrame_set_index.ipynb)** |
|    | 1.10 **[Python_Pandas_DataFrame_reset_index](pandas/001_Python_Pandas_Methods/010_Python_Pandas_DataFrame_reset_index.ipynb)** |
| 02 | **[Python_Pandas_Exercise_1](pandas/002_Python_Pandas_Exercise_1.ipynb)** |
| 03 | **[Python_Pandas_Exercise_2](pandas/003_Python_Pandas_Exercise_2.ipynb)** |
|    | **[automobile_data.csv](pandas/automobile_data.csv)** |
|    | **[pokemon_data.csv](pandas/pokemon_data.csv)** |
| 04 | **[Pandas Cheat Sheet Data Wrangling in Python.pdf](pandas/Pandas%20Cheat%20Sheet%20Data%20Wrangling%20in%20Python.pdf)** |
| 05 | **[Pandas Cheat Sheet for Data Science in Python.pdf](pandas/Pandas%20Cheat%20Sheet%20for%20Data%20Science%20in%20Python.pdf)** |

---

## Install Pandas Module:

 -       pip install pandas  
 

Once Installed now we can import it inside our python code.

# Web-scraping using BeautifulSoup

This notebook includes data scraping, for this beautifulsoup and selinium is used. It which takes a website URL as an input and extracts the information listed below as an output from that webpage.
1. Specific HTML tags along with titles and meta description
2. Extract specific tags, heading tags from h1-h6 along with titles and meta description
3. Extracting ALT tags
4. Counting words inside a web page
5. Inspection of broken links inside a webpage
6. Extracting the source code of the webpage in google colab
7. Extracting all URLs from a website without duplication
8. Measuring the forntend and backend performance of website

## [Tutorial for Web-scraping using beautifulsoup](web-scraping/Web_Scraping_using_python_and_beautifulsoup.ipynb)


# [Working with APIs & JSON](https://www.youtube.com/watch?v=7vrayxFYY2w)

# [Basics of SQL for data extraction  ](https://www.youtube.com/watch?v=OT1RErkfLNQ)
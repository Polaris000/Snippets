## Snippets


### About
A collection of snippets and functions that I regularly use in my workflows as a data scientist. These snippets are utility functions that speed up my work, and focus on Pandas, Numpy and visualization libraries.


### Pandas
| Snippet  | Code | Description |
| ------------- | ------------- | ------------ |
| ![](https://img.shields.io/badge/NEW-success/?style=flat-square) Boosted value_counts | [Code](./pandas/boosted_value_counts.ipynb)| This function improves the `value_counts` function by outputing absolute and normalized counts simultaneously, for faster analysis. It also sets the default value of `dropna` to False, so any NaNs that exist easily spotted.|
| ![](https://img.shields.io/badge/NEW-success/?style=flat-square) Pandarallel Configuration| [Code](./pandas/pandarallel_config.ipynb)| Pandas isn't great when it comes to handling large amounts of data, mainly because it natively uses only a single core. Pandarallel is a very straightforward alternative to parallelize pandas code. |



### IPython + Miscellaneous
| Snippet  | Code | Description |
| ------------- | ------------- | ------------ |
| ![](https://img.shields.io/badge/NEW-success/?style=flat-square) Color print in jupyter notebooks | [Code](./ipython/color_print.ipynb)| Coloring specific values in your output can be an easy way to highlight important information. While there are packages like `termcolor` or `colorama`, I find that simply using ANSI color outputs works best. |
| ![](https://img.shields.io/badge/NEW-success/?style=flat-square) Progress bars in jupyter notebooks | [Code](./ipython/tqdm_config.ipynb)| `tqdm` is a package that lets you create progress bars. While it has notebook specific versions via `tqdm_notebook`, I find that directly using `tqdm` works just as well without the hassle of setting up `ipywidgets` and `IProgress`.|
# `src` package overview

All functions for this project, should be stored in this folder. All tests should be
stored in the `tests` folder, which is one-level above this folder in the main project
directory.

The sub-folders should be used as follows:

- `dao`: data access functions
- `data`: data processing-related functions
- `features`: feature-related functions, for example, functions to create features
  from processed data
- `models`: model-related functions
- `visualizations`: functions to produce visualizations
- `utils`: utility functions that are helpful in the project

Feel free to create/rename/delete these folders as required, as they will not be
necessary for each and every project.

It is strongly suggested that you import functions in the `src/__init__.py` script. You
should also try to use absolute imports in this script whenever possible. Relative
imports are not discouraged, but can be an issue for projects where the directory
structure is likely to change. See [PEP 328 for details on absolute imports][pep-328].
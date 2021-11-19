## Overview

The `py.exe` is a command line toll that comes with Python installation that help us doing version management.
## Usage

After installing Python on Windows, then we can use the `py` command for version management.

```bash
# list all python installations available
$ py -0

# run python with given version
$ py -3.7
```

This would be helpful for creating the virtual environments with specific Python version.

```bash
# create virtual environment with Python 3.8
$ py -3.8 -m venv env
```
- ## References
	- [Manage multiple Python versions on Windows with py.exe](https://changhsinlee.com/windows-py-launcher/)
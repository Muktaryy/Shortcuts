# Python Command Checklist

A practical checklist to learn Python commands, interpreter usage, virtual environments, package management, testing, code quality, data science, and package publishing.

## 01. Python and Interpreter

* [ ] `python --version` — Display the installed Python version
* [ ] `python --help` — Display command-line options
* [ ] `python` — Start the interactive Python interpreter
* [ ] `python -c "print('Hello')"` — Execute a Python statement directly
* [ ] `python -m` — Run a library module as a script
* [ ] `where python` — Find Python executables (Windows CMD)
* [ ] `Get-Command python` — Locate Python commands (PowerShell)
* [ ] `which python` — Locate Python on Linux/macOS

## 02. Running Python Files

* [ ] `python main.py` — Run a Python script
* [ ] `python -u main.py` — Run with unbuffered standard output and error
* [ ] `python -i main.py` — Run a script and enter interactive mode afterward
* [ ] `python -m module_name` — Execute a module as a script
* [ ] `python -m package_name` — Execute a package through its `__main__.py`

## 03. Virtual Environments

* [ ] `python -m venv .venv` — Create a virtual environment
* [ ] `.\.venv\Scripts\Activate.ps1` — Activate the environment in PowerShell
* [ ] `.venv\Scripts\activate.bat` — Activate the environment in Windows CMD
* [ ] `source .venv/bin/activate` — Activate the environment on Linux/macOS
* [ ] `deactivate` — Leave the active virtual environment
* [ ] `python -m venv --help` — View virtual environment options

## 04. pip and Packages

* [ ] `python -m pip --version` — Display the pip version
* [ ] `python -m pip install requests` — Install a package
* [ ] `python -m pip uninstall requests` — Uninstall a package
* [ ] `python -m pip list` — List installed packages
* [ ] `python -m pip show requests` — Display package details
* [ ] `python -m pip freeze` — List installed packages in requirements format
* [ ] `python -m pip install -r requirements.txt` — Install dependencies from a file
* [ ] `python -m pip check` — Check for incompatible dependencies
* [ ] `python -m pip install --upgrade pip` — Upgrade pip

## 05. Dependencies and Project Setup

* [ ] `requirements.txt` — Record project dependencies
* [ ] `python -m pip freeze > requirements.txt` — Export installed packages to a file
* [ ] `python -m pip install -r requirements.txt` — Install recorded dependencies
* [ ] `pyproject.toml` — Configure project metadata and Python tooling
* [ ] `.python-version` — Specify a Python version for compatible tools
* [ ] `.gitignore` — Tell Git which files to ignore
* [ ] `.venv/` — Keep the virtual environment in a local project directory

## 06. Imports and Modules

* [ ] `python -m package_name` — Run a package as a program
* [ ] `python -c "import math; print(math.pi)"` — Import a module and print a value
* [ ] `python -c "import sys; print(sys.executable)"` — Display the active Python executable
* [ ] `python -c "import sys; print(sys.path)"` — Display Python's module search paths
* [ ] `python -m compileall .` — Compile Python files to bytecode
* [ ] `python -m site` — Display Python site and package directory information

## 07. Testing and Debugging

* [ ] `python -m unittest` — Run unit tests
* [ ] `python -m unittest discover` — Discover and run unit tests
* [ ] `python -m pdb main.py` — Run a script with the Python debugger
* [ ] `breakpoint()` — Pause execution at a debugging breakpoint
* [ ] `python -X dev main.py` — Enable Python development mode
* [ ] `python -W error main.py` — Treat warnings as errors

## 08. Code Quality and Formatting

* [ ] `python -m pytest` — Run tests with pytest
* [ ] `python -m ruff check .` — Check code with Ruff
* [ ] `python -m ruff format .` — Format code with Ruff
* [ ] `python -m black .` — Format Python files with Black
* [ ] `python -m mypy .` — Check types with mypy
* [ ] `python -m pylint main.py` — Analyze code with Pylint

*Note: Install the relevant tools in your active environment before running them.*

## 09. Jupyter and Data Science

* [ ] `python -m pip install jupyterlab` — Install JupyterLab
* [ ] `jupyter lab` — Launch the JupyterLab interface
* [ ] `python -m pip install ipykernel` — Install the IPython kernel package
* [ ] `python -m ipykernel install --user --name myenv` — Register a named kernel
* [ ] `python -m pip install numpy pandas matplotlib` — Install common data science libraries

## 10. Build and Publish Packages

* [ ] `python -m build` — Build source and wheel distributions
* [ ] `python -m pip install build` — Install the build frontend
* [ ] `python -m pip install twine` — Install a package upload and distribution checker
* [ ] `python -m twine check dist/*` — Check package distribution metadata
* [ ] `python -m pip install -e .` — Install a local project in editable mode

## 11. Environment Variables

* [ ] `$env:NAME = "value"` — Set an environment variable in PowerShell
* [ ] `$env:NAME` — Read an environment variable in PowerShell
* [ ] `Remove-Item Env:NAME` — Remove an environment variable in PowerShell
* [ ] `echo %NAME%` — Read an environment variable in Windows CMD
* [ ] `set NAME=value` — Set an environment variable in Windows CMD
* [ ] `export NAME=value` — Set an environment variable in Linux/macOS shells
* [ ] `import os; os.getenv("NAME")` — Read an environment variable from Python

## 12. Python Tooling

* [ ] `py --list` — List Python installations using supported Windows launchers
* [ ] `uv --version` — Display the uv version
* [ ] `uv venv` — Create a virtual environment using uv
* [ ] `uv add requests` — Add a dependency to a uv-managed project
* [ ] `uv run main.py` — Run a script in a uv-managed environment
* [ ] `conda --version` — Display the Conda version
* [ ] `conda create -n myenv python=3.12` — Create a Conda environment
* [ ] `conda activate myenv` — Activate a Conda environment

---

## Progress Tracker

* **Total checklist items:** 79
* **Completed:** 0
* **Goal:** Learn each command, understand when to use it, and practice it in real Python projects.

## Learning Resources

* [Official Python Documentation](https://docs.python.org/3/)
* [Python Tutorial](https://docs.python.org/3/tutorial/)
* [Python Packaging User Guide](https://packaging.python.org/)
* [pip Documentation](https://pip.pypa.io/en/stable/)
* [pytest Documentation](https://docs.pytest.org/)
* [uv Documentation](https://docs.astral.sh/uv/)
* [Conda Documentation](https://docs.conda.io/)

---

## Practice Tips

* Use a virtual environment for each project.
* Prefer `python -m pip` to help ensure pip belongs to the selected Python interpreter.
* Never commit `.venv/`, API keys, or other secrets to Git.
* Install development tools before using their `python -m` commands.
* Check which Python interpreter is active when troubleshooting package issues.
* Remember that commands and activation syntax vary across Windows, Linux, and macOS.

⭐ **Keep coding, keep experimenting, and build your Python skills one command at a time!**

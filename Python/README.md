# Python

[Official website](https://www.python.org/)
this code sample is meant for Python 3.

It's better to use Python 3 since version 2 is considered legacy (last version, 2.7 was out in 2007) and won't be updated.
Also Python 3 remove many issues from python 2 (algebra, unicode, etc).

python have an interactive mode (just type python3 in command line)

## package

Python have a package installer named pip
Documentation is [here](https://pip.pypa.io/en/stable/).
You can browse package [here](https://pypi.python.org/pypi).

```bash
pip3 install [package]
pip3 install --user [package] #gobal installation
pip3 uninstall [package]
```

Python also provide a containerized environment called virtualenv.
Virtualenv is not installed by default.

For required package in a project:

```bash
pip install -r requirements.txt
```

[example](example-requirements.txt)

## Virtual environment

A good practice is to use a virtual environment: it's an independent python environment, allowing you to calibrate libraries for each projects

```bash
#creation of a new environment
python3 -m venv /path/to/new/virtual/environment

#using a virtual environment
source /path/to/the/environment
#console should now look like this:
(myenv) user@host~:$
#by now you can call any program using python3 /myprogram.py

#to quit the virtual environment, just type in command line
deactivate
```

## Convention

Style convention for python is PEP 8
[available here](https://www.python.org/dev/peps/pep-0008/)
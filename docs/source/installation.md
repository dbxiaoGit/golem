Installation
==================================================

##### Requirements

Golem requires Python 3.4 or higher. You may download and install it from here [python.org/downloads/](http://www.python.org/downloads/)

PIP is required to install it, check if you already have it, it should come bundled with Python

```
pip --version
```

If you don't have PIP installed, follow [these instructions](https://pip.pypa.io/en/stable/installing/).

##### Using virtualenv (optional)

It is recommended to install Golem and it's dependencies in a [virtual environment](http://www.virtualenv.org/en/latest/) instead of globally. To do that, follow this steps:

```
pip install virtualenv
virtualenv env
```

- **Windows**:

```
env\scripts\activate
```

- **Mac/Linux**:

```
source env/bin/activate
```

##### Install Using PIP

```
pip install https://github.com/lucianopuccio/golem/archive/0.1.1.tar.gz
```


##### Install From Source

**1. Clone the Golem repo locally**

```
git clone https://github.com/lucianopuccio/Golem.git golem
```

**2. Install using setup.py**

```
cd golem
python setup.py install
```

Next, go to [Quick Start](quick-start.html)
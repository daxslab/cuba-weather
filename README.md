# cuba-weather

Python3 client for [redcuba.cu](https://www.redcuba.cu) weather API

## Install

`pip install git+https://github.com/daxslab/cuba-weather`

## Usage

```
usage: cuba-weather.py [-h] [-v] [-d] [-t] [-u] [-p] [-w] [-g] location

positional arguments:
  location           location name

optional arguments:
  -h, --help         show this help message and exit
  -v, --version      show program version
  -d, --date         show location date
  -t, --temperature  show location temperature
  -u, --humidity     show location humidity
  -p, --pressure     show location pressure
  -w, --wind         show location wind
  -g, --general      show location general information
```

When just speciying the location and no other arguments, all the available information is displayed.


# Download-neuromorpho.org
A Python package to download http://neuromorpho.org/

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/RoozbehFarhoodi/Download-neuromorpho.org/blob/master/LICENSE)

Having trouble while downloading neuromorpho's data! use this code to get them all in a nice dataframe format!
It downloads the swc as well as all the metadata that exist for a given neuron. 
e.g. http://neuromorpho.org/neuron_info.jsp?neuron_name=5038801

## Install package

Clone the repository

```bash
$ git clone ps://github.com/RoozbehFarhoodi/Download-neuromorpho.org
$ cd Download-neuromorpho.org/
```

### Dependencies
```python
urllib
ast
numpy
pandas
re
json
urllib2
bs4
unidecode
```

### Usage

After installing, open a note book and write:

```python
import dnm
neurons = dnm.download_neuromorpho(start_nmo=0, end_nmo=10)
```

```neurons``` gives the database of all the neuron if the range of downloading.

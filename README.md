# EnergyDemand

The tool is an extension of the enviroCar Python package and allows users to download the trajectory data and estimate the energy demand and co2 emission along tracks. The tool enables users to set their car's parameters and elaborate on elevation accuracy, driving efficiency, and the track's pavement. 

The extension currently only supports users to estimate the energy demand and co2 emission value of download track data. It is intended to further expand these functionalities with additional analytics in the future.

## Installation

The package requires a Python version >= 3.6. The package is available on the PyPI package manager and can be installed with the following command:

```
pip install envirocar-py --upgrade
```

To install envirocar-py in develop mode, use the following:

```
python setup.py develop
```

If the extension hasn't included in the envirocar-py, you can install it manully by the steps:
Download the <b> folder</b> by the [link](https://github.com/masawdah/enrgydemand/tree/master/envirocar/client/fuel)
and the files <b> required_functions.py , request_param.py </b>
from the [folder](https://github.com/masawdah/enrgydemand/tree/master/envirocar/client)
Finally, put the files under your local envirocar/client folder


## Examples
The example of the extension can be found [here](https://github.com/masawdah/enrgydemand/blob/master/examples/python_tool_example.ipynb)

The step by step calculation can be found in the example [folder](https://github.com/masawdah/enrgydemand/blob/master/examples/Energy_demand.ipynb)


## License ##
    MIT License

    Copyright (c) 2020 The enviroCar Project

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
    of the Software, and to permit persons to whom the Software is furnished to do
    so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

<!-- <img src="docs/source/logo/BluePyOptBanner.png"/> -->

-----------------

# BluePyEfe: Blue Brain Python E-feature extraction

<table>
<tr>
  <td>Latest Release</td>
  <td>
    <a href="https://pypi.org/project/bluepyefe/">
    <img src="https://img.shields.io/pypi/v/bluepyefe.svg" alt="latest release" />
    </a>
  </td>
</tr>
<tr>
  <td>Documentation</td>
  <td>
    <a href="https://bluepyefe.readthedocs.io/">
    <img src="https://readthedocs.org/projects/bluepyefe/badge/?version=latest" alt="latest documentation" />
    </a>
  </td>
</tr>
<tr>
  <td>License</td>
  <td>
    <a href="https://github.com/BlueBrain/bluepyefe/blob/master/LICENSE.txt">
    <img src="https://img.shields.io/pypi/l/bluepyefe.svg" alt="license" />
    </a>
</td>
</tr>
<tr>
  <td>Build Status</td>
  <td>
    <a href="https://travis-ci.org/BlueBrain/BluePyEfe">
    <img src="https://travis-ci.org/BlueBrain/BluePyEfe.svg?branch=master" alt="travis build status" />
    </a>
  </td>
</tr>
<tr>
  <td>Coverage</td>
  <td>
    <a href="https://codecov.io/gh/BlueBrain/bluepyefe">
    <img src="https://codecov.io/github/BlueBrain/BluePyefe/coverage.svg?branch=master" alt="coverage" />
    </a>
  </td>
</tr>
<tr>
	<td>Gitter</td>
	<td>
		<a href="https://gitter.im/bluebrain/bluepyefe">
		<img src="https://badges.gitter.im/Join%20Chat.svg"
	</a>
	</td>
</tr>
</table>

Introduction
============

BluePyEfe aims at easing the process of reading experimental recordings and extracting 
batches of efeatures from these recordings. To do so, it combines trace reading
functions and features extraction functions from the [eFel library](https://github.com/BlueBrain/eFEL).

BluePyEfe outputs protocols and features files in the format used
by [BluePyOpt](https://github.com/BlueBrain/BluePyOpt) for neuron electrical
 model building.

Requirements
============

* [Python 3.6+](https://www.python.org/downloads/release/python-360/) (still compatible with [Python 2.7+](https://www.python.org/download/releases/2.7/))
* [Pip](https://pip.pypa.io) (installed by default in newer versions of Python)
* [eFEL eFeature Extraction Library](https://github.com/BlueBrain/eFEL) (automatically installed by pip)
* [Numpy](http://www.numpy.org) (automatically installed by pip)
* [Pandas](http://pandas.pydata.org/) (automatically installed by pip)
* [Scipy](https://www.scipy.org/) (automatically installed by pip)
* [Neo](https://neo.readthedocs.io/en/stable/) (automatically installed by pip)
* The instruction below are written assuming you have access to a command shell
on Linux / UNIX / MacOSX / Cygwin

Installation
============

To install BluePyEfe, clone the repository, enter the resulting directory, and
 run:

```bash
pip install -e .
```

Quick Start
===========

For a quick start, have a look at the notebook examples/example.ipynb

Funding
=======
This work has been partially funded by the European Union Seventh Framework Program (FP7/2007­2013) under grant agreement no. 604102 (HBP), the European Union’s Horizon 2020 Framework Programme for Research and Innovation under the Specific Grant Agreement No. 720270, 785907 (Human Brain Project SGA1/SGA2).

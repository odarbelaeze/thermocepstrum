# thermocepstrum
Code to compute thermal conductivity through cepstral analysis of heat flux time series, as described in papers:
 - Ercole, Marcolongo, Baroni, Sci. Rep. 7, 15835 (2017), https://doi.org/10.1038/s41598-017-15843-2
 - for the multi-component analysis:  Baroni, Bertossa, Ercole, Grasselli, Marcolongo, https://arxiv.org/abs/1802.08006

**Acknowledgement**  The development of this software is part of the scientific program of the EU MaX Centre of Excellence for Supercomputing Applications (Grant No. 676598) and has been partly funded through it.

### Usage
The code can be used as a **library**, for example in a Jupyter notebook. 
In the `examples` folder you can find some examples. 

Alternatively, you can run the code `analysis.py` from the **command line**.
It can execute most of the cepstral analysis routines, returning the results in a series of data files and PDF plots.
See the `examples` folder and the help (`python analysis.py --help`) for more information.

### Requirements
 - Python 2.7
 - Numpy
 - Scipy
 - Matplotlib

### Installation
  1. Clone this repository `git clone https://github.com/lorisercole/thermocepstrum.git`
  2. Install the package with pip (dependencies will be automatically downloaded). For example:
```
cd thermocepstrum
pip install .
```
  3. You are done! You can check that the installation is working by trying to run the command `thermocepstrum-analysis`.

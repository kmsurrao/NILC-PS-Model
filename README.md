# NILC-PS-Model
Computation of power spectra of NILC component-separated maps, using n-point functions.

## Requirements and Set-up
 - Requires a clone of the pyilc repository (https://github.com/jcolinhill/pyilc). 
 - Requires a CMB map .fits file in Kelvin (lensed alm can be downloaded from WebSky at https://mocks.cita.utoronto.ca/data/websky/v0.0/). 
 - Requires a tSZ map in .fits file format in units of Kelvin, which can be generated via halosky (https://github.com/marcelo-alvarez/halosky) or downloaded from Websky.
 - Modify one of the example yaml files or create a similar one, modifying paths to the above requirements and any additional specifications.

## Running      
```python main.py --config=example_yaml_files/[FILENAME].yaml```  

Various files are saved when running the main pipeline. The Jupyter Notebook [plotting_examples.ipynb](plotting_examples.ipynb) can then be used to construct relevant plots.  

## Dependencies
python >= 3.7  
pywigxjpf    
pyyaml   
healpy   

## Acknowledgments
Portions of this code are adapted from PolyBin (https://github.com/oliverphilcox/PolyBin), pyilc (https://github.com/jcolinhill/pyilc), and reMASTERed (https://github.com/kmsurrao/reMASTERed).



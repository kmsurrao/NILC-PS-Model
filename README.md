# NILC-PS-Model
Computation of power spectra of NILC component-separated maps, using n-point functions.

## Requirements and Set-up
 - Requires a clone of the pyilc repository (https://github.com/jcolinhill/pyilc). 
 - Requires a CMB map .fits file in Kelvin (lensed alm can be downloaded from WebSky at https://mocks.cita.utoronto.ca/data/websky/v0.0/). 
 - Requires a tSZ map in .fits file format in units of Kelvin, which can be generated via halosky (https://github.com/marcelo-alvarez/halosky) or downloaded from Websky.
 - Modify example.yaml or create a similar yaml files, modifying paths to the above requirements and any additional specifications.

## Running      
```python main.py --config=example_yaml_files/[FILENAME].yaml```  

## Recommendations
It is recommended (though not required) to comment out calls to healpy mollview in pyilc/pyilc/wavelets.py.

## Dependencies
python >= 3.7  
pywigxjpf    
pyyaml   
healpy   

## Acknowledgments
Portions of this code are adapted from PolyBin (https://github.com/oliverphilcox/PolyBin), pyilc (https://github.com/jcolinhill/pyilc), and reMASTERed (https://github.com/kmsurrao/reMASTERed).



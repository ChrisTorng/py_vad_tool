Forked from
===========

https://github.com/idnavid/py_vad_tool

Windows
=======
```
python -m venv .venv
.venv\Scripts\activate
pip install numpy scipy matplotlib
python unsupervised_vad.py
```

### py_vad_tool
This is a light-weight python script for voice activity detection. 
The VAD is energy-based. This code can be used for large corpora for applicatoins such as
Speaker ID, Language ID, etc. 

The only prerequisits are `numpy`, `scipy` and `matplotlib`.

Additionally, for debugging purposes, you can use `pylab`. 

To run demo, try: 
```
python unsupervised_vad.py 
```
This will run energy-based vad on the sample file in data. The two plots are 
frame-based energy values and sample-based decisions, in that order. 

Feel free to use this script in any capacity. 
NS

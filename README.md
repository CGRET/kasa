# kasa
Sample code for kasa using [pyHS100](https://github.com/GadgetReactor/pyHS100)

Create a conda environment and install the pyHS100 package:
```bash
conda create --name kasa python=2
conda activate kasa
pip install pyHS100
```

You'll need the IP address or host name of the device you want to control.  
For example the IP address of the HS300 powerstrip I'm using is 10.10.0.239 (hostname is HS300).  
To query it's power usage:
```bash
phys100 --host 10.10.0.239 emeter
```
Which produces JSON output.

# References
 * [pyHS100](https://github.com/GadgetReactor/pyHS100)

## IPSG - Invariant proof scores generation. 

IPSG is implemented on top of CafeInMaude (https://github.com/ariesco/CafeInMaude), which is the world's second implementation of CafeOBJ.
IPSG requires Maude version not lower than Maude 3.2 (https://github.com/SRI-CSL/Maude).
To run the tool, first you need to install Maude, which can be found from here: http://maude.cs.illinois.edu/w/index.php/Maude_download_and_installation.
Once Maude is installed, you can try to run the tool with the following commands:

```
maude -allow-files ipsg.maude
load examples/Qlock/qlock.cafe .
load examples/Qlock/input1.cafe .
```

where the first command starts the tool, the second command loads the Qlock specification, the last command loads the input file, which asks the tool to generate the proof score for `inv1` of Qlock.
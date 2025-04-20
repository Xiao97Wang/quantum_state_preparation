# QPrep (stablized environment)
A library devoted to quantum state preparation via tensor netwokrs. As an input it takes a function and number of qubits and returns a qiskit circuit for preparing the quantum state.

![QPrep bench](img/results.jpg)

## Requirements
TensorFlow >= 2.0 
- qiskit (https://github.com/Qiskit/qiskit)
- ttpy (https://github.com/oseledets/ttpy) 
- QGOpt (https://github.com/LuchnikovI/QGOpt)
- Cotengra (https://github.com/jcmgray/cotengra)
- TensorNetwork (https://github.com/google/TensorNetwork)




## Installation

This only works in linux. First, make sure gcc and gfortran is installed in linux. 

Then, create an env in conda, with python=3.9
```
   conda create --name QPrep python=3.9
   conda activate QPrep
```

Then, install ttpy USING Conda:
```
   conda install numpy==1.19.5 cython=3.0.11
   pip install ttpy
```

Then, download the repo, and build the STABLIZED "requirements.txt"
```
   git clone https://github.com/Xiao97Wang/quantum_state_preparation.git
   pip install -r quantum_state_preparation/requirements.txt
```

Then, in the directory 'quantum_state_preparation', open python, and then the function qprepfn can be correctly imported


## Example
An example of using our method is available right now in example.ipynb

## Related publications
Coming soon
## Authors
This package is made by [Termanova A.A.](https://github.com/AlenaAT), [Melnikov Ar.A.](https://github.com/Arty1498) and [Perelshtein M.R.](https://github.com/mperelshtein)


# Interactive Wrapper for the Class p(k) Computation

This repository contains a Jupyter notebook and an environment file for the notebook to run properly.

## Getting Started

### Clone this Repository:

```bash
git clone https://github.com/rchgomes/interactive_pk.git 
cd interactive_pk
```

### Create a Conda Environment from the .yml File:

```bash
conda env create -f class_env.yml 
conda activate basic_env
```

### Open the Jupyter Notebook:

```bash
jupyter notebook Interactive_pk.ipynb
```

### Troubleshooting CLASSY Installation:

If you encounter problems with CLASSY when installing the .yml file, run the following commands:

```bash
git clone https://github.com/lesgourg/class_public.git 
cd class_public 
make clean 
make 
cd python 
python setup.py install 
python setup.py install --user
```
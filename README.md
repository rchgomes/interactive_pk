# Interactive wrapper for the class p(k) computation

This repository contains a Jupyter notebook and an environment file for your cosmology project.

## Getting Started

1. Clone this repository:

   git clone https://github.com/rchgomes/interactive_pk.git
   cd interactive_pk

2. Create a conda environment from the .yml file:

	conda env create -f class_env.yml
	conda activate basic_env

3. Open the Jupyter notebook:

	jupyter notebook Interactive_pk.ipynb

4. If you encounter problems with CLASSY when installing the .yml file, run the following commands:

	git clone https://github.com/lesgourg/class_public.git
	cd class_public
	make clean
	make
	cd python
	python setup.py install
	python setup.py install --user

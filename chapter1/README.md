# Instructions to run the code
This example has been provided in a Jupyter Notebook with a virtual environment created with venv.

    python -m venv env

To activate the virtual environment *myenv*

    source myenv/bin/activate

Then, to be able to run the notebook inside the virtual environment, let's install jupyter:

    pip install notebook ipkernel

Add the virtual environment as a Jupyter kernel

    python -m ipkernel install --user --name=myenv --display-name "Python (myenv)"

Start the jupyter Notebook by:

    jupyter notebook

Select the kernel: When you open a notebook, go to the "Kernel" menu, select "Change Kernel" and choose Python (myenv).
## Cytoscape Automation

Here is a collection of various demos using techniques to Automate Cytoscapes functionality.

### py2cytoscape

In order to run the py2cytoscape demo: `py2cytoscape_demo_tps.ipynb`, first set up environment and kernel.
The py2cytoscape demo is an updated tutorial for py2cytoscape 0.7.1. Further comments about work arounds are in the jupyter notebook file

cd into `NetworkVisualization/CytoscapeAutomation`

create environment

`conda env create -f environment.yml`

Activate environment by calling `conda activate py2cyto_sandbox`

Next, add conda environment to Jupyter by typing:

`python -m ipykernel install --user --name=py2cyto-sandbox`
  
This should print:

`Installed kernelspec myenv in /home/user/.local/share/jupyter/kernels/py2cyto_sandbox`

check to see available kernels

`jupyter kernelspec list`

Check to see that py2cyto_sandbox appears

Deactivate py2cyto_sandbox (env should have been activated during above steps) and call `jupyter notebook` 


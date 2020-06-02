# Cytoscape Automation

Here is a collection of various demos using techniques to Automate Cytoscapes functionality.

## py2cytoscape 
<a id="1">[1]</a>
[documentation](https://py2cytoscape.readthedocs.io/en/latest/)

### cyREST documentation:
<a id="1">[2]</a> 
Ono, Keiichiro, et al. [CyREST: Turbocharging Cytoscape Access for External Tools via a RESTful API](https://f1000research.com/articles/4-478/v1). F1000Research 4 (2015).

### Setup 

In order to run the py2cytoscape demo: `py2cytoscape_demo_tps.ipynb`, first set up environment and kernel.
The py2cytoscape demo is an updated tutorial for py2cytoscape 0.7.1. Further comments about work arounds are in the jupyter notebook file

cd into
```bash 
NetworkVisualization/CytoscapeAutomation
```

create environment

```bash
conda env create -f environment.yml
```

Activate environment by calling 
```bash
conda activate py2cyto_sandbox
```

Next, add conda environment to Jupyter by typing:

```bash
python -m ipykernel install --user --name=py2cyto_sandbox
```
  
This should print:

```bash
Installed kernelspec py2cyto_sandbox in /home/user/.local/share/jupyter/kernels/py2cyto_sandbox
```

check to see available kernels

```bash 
jupyter kernelspec list
```

Check to see that py2cyto_sandbox appears

Deactivate py2cyto_sandbox (env should have been activated during above steps) and call `jupyter notebook` 

Select `py2cyto_sandbox as kernel`

## ipycytoscape

Cytoscape widget for jupyter notebook.

<a id="1">[3]</a> 
[ipycytoscape article](https://blog.jupyter.org/interactive-graph-visualization-in-jupyter-with-ipycytoscape-a8828a54ab63)


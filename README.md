[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ncbi/workshop-mol-evol-datasets/master?labpath=notebooks%2Fworkshop.ipynb)

# Introduction to molecular evolutionary analysis with NCBI Datasets and Python

### Created by Daniel Rice and Mirian Tsuchiya, Summer 2022

As they diverge from a common ancestor, species accumulate differences in their DNA sequences. Differences within a protein-coding region are classified in two types. Non-synonymous substitutions change the amino acid sequence of the protein, while synonymous substitutions do not. Synonymous substitutions are largely invisible to natural selection and tend to accumulate at a constant rate. On the other hand, non-synonymous substitutions whose effects are beneficial accumulate at a faster rate, while those that are deleterious are suppressed. By comparing the rates of non-synonymous and synonymous substitutions, we can infer whether natural selection has primarily acted to conserve the protein sequence or to adapt it to a new environment or function.

In this workshop you will learn to compare the protein-coding sequences of two species to estimate which proteins show signs of adaptation. Working in a Jupyter notebook with bash and Python, you will use the NCBI Datasets command line interface (CLI) to download sequence data, then perform analysis with a few popular Python packages. The workshop assumes basic familiarity with a scripting language such as Python or R at a level equivalent to a semester course or programming bootcamp.

## Learning objectives:
In this workshop you will learn how to:
- Search for and download protein ortholog sequences with NCBI Datasets CLI
- Parse the downloaded files with BioPython
- Identify synonymous and non-synonymous substitutions and calculate substitution rates
- Plot the results with Matplotlib

## Materials:

We will be using [The Littlest JupyterHub](https://tljh.jupyter.org/en/latest/index.html) to serve Jupyter notebooks to a class of 30--50 students.

### Recovering a broken notebook
If a student changes their notebook so it won't run and can't undo the changes:
- Rename the notebook by clicking on the title "workshop" at the very top of the page.
  It doesn't matter what name they choose.
- Click the workshop link again to download a fresh copy.

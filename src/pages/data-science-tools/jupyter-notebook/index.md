---
title: Jupyter Notebook
---
## Jupyter Notebook

The Jupyter Notebook helps you create and share documents containing live code, equations, visualizations and rich text.   
 
You can use it for:
* data cleaning and transformation
* numerical simulation
* statistical modeling
* data visualization
* machine learning

The Jupyter notebook combines two components:

### A web application:  

The Jupyter Notebook App helps to edit and run notebook documents in a web browser,  combining explanatory text, mathematics, computations and rich media.

### Notebook document:

The Jupyter Notebook App can create a 'Notebook document' containing both code and rich text elements. A Notebook document can be both readable and executable.

These documents are produced by the Jupyter Notebook App.

## Jupyter Notebook App
As a server-client application, the Jupyter Notebook App allows you to edit and run your notebooks via a web browser.  
The application can be executed on a PC without Internet access or it can be installed on a remote server, where you can access it through the Internet.  

Its two main components are the kernels and a dashboard.

### Kernels
A kernel is a program that runs and introspects the user’s code. The Jupyter Notebook App has a kernel for Python code, but there are also kernels available for other programming languages.

### Dashboard
The dashboard of the application not only shows you the notebook documents that you have made and can reopen but can also be used to manage the kernels: you can which ones are running and shut them down if necessary.

### How notebooks work
Jupyter notebooks grew out of the IPython project started by Fernando Perez. IPython is an interactive shell, similar to the normal Python shell but with great features like syntax highlighting and code completion. Originally, notebooks worked by sending messages from the web app (the notebook you see in the browser) to an IPython kernel (an IPython application running in the background). The kernel executed the code, then sent it back to the notebook.
![Notebook architecture](https://jupyter.readthedocs.io/en/latest/_images/notebook_components.png)

When you save the notebook, it is written to the server as a JSON file with a **.ipynb** file extension
The new name Jupyter comes from the combination of **Ju**lia, **Py**thon, and **R**. there are a lot of kernels for different languages to use Jupyter. you could check the [list of available Jupyter kernels](https://github.com/jupyter/jupyter/wiki/Jupyter-kernels).

### Installing Jupyter Notebook
Jupyter notebooks automatically come with the distribution. You'll be able to use notebooks from the default environment.
To install Jupyter notebooks in a conda environment: `conda install jupyter notebook`
To install Jupyter notebooks with pip: `pip install jupyter notebook`

#### More Information:
* [Jupyter/IPython Notebook Quick Start Guide](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)
* [What is Jupyter Notebook by codebasics, duration 8:24](https://www.youtube.com/watch?v=q_BzsPxwLOE)
* [Jupyter Notebook Tutorial / Ipython Notebook Tutorial, by codebasics, duration 24:07](https://www.youtube.com/watch?v=EEEZX_0FMEc)
* [More Information](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)

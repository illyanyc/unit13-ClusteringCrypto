![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&width=1000&height=200&section=header&text=Clustering%20Crypto&fontSize=30&fontColor=black)

<!-- header is made with: https://github.com/kyechan99/capsule-render -->

[Illya Nayshevsky, Ph.D.](http://www.illya.bio) [<img src="https://cdn2.auth0.com/docs/media/connections/linkedin.png" alt="LinkedIn -  Illya Nayshevsky" width=15/>](https://www.linkedin.com/in/illyanayshevskyy/)

<br>
Columbia FinTech Bootcamp Assignment

---

### Table of Contents
* [Overview](#overview)
* [Requirements](#requirements)
* [Data](#data)


---

## Overview


## Requirements

A new conda environement should be used. The analysis is written in a Jupyter notebook. Data visualization is done with Plotly and hvPlot. 

[Node.js v14.17.0](https://nodejs.org/en/) or higher is required to build Jupyter Lab Extentions.

```python
conda install -c conda-forge jupyterlab

pip install pandas
pip install matplotlib
pip install -U scikit-learn

conda install hvplot
conda install -c plotly plotly
conda install "notebook>=5.3" "ipywidgets>=7.5"
jupyter labextension install jupyterlab-plotly@4.14.3
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.14.3


```
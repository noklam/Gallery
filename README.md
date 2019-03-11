Data Source:
https://hackmd.io/W2MH0_-dQKa8enw9M83iTA?fbclid=IwAR3YDUJrjllpwetMv3ok216OqE45v7ONKRLI3k_Ak1vajvqwfssyoZjzDQM

Render HTML on Github
https://htmlpreview.github.io/
or
https://noklam.github.io/Gallery/xxxx.html
## Make sure you install ipywidgets for Jupyter Notebook or install nodejs for JupyterLab, if you did not install the ipywidgets, you will see nothing render when you run the code.

## NodeJS
```
conda config --add channels conda-forge
conda install nodejs
```

## Install Extension
```
pip install jupyter_contrib_nbextensions && jupyter contrib nbextension install 
pip install jupyter_nbextensions_configurator
jupyter nbextensions_configurator enable --user
```
## Jupyter Notebook
```
jupyter nbextension enable --py widgetsnbextension
```
## Jupyter Lab
```
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

## qgrid
```
jupyter labextension install qgrid
pip install qgrid
```

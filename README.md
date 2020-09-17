[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/davidrpugh/jupytercon-2020-talk/nvidia-rapids-env)

# JupyterLab + NVIDIA RAPIDS + BlazingSQL + Dask

Contains configuration files for a JupyterLab-based data science project using [NVIDIA RAPIDS](https://rapids.ai/), 
[BlazingSQL](https://www.blazingsql.com/), and [Dask](https://dask.org/). You can explore the JupyterLab UI/UX via 
Binder by clicking the "launch binder" button above, but the instance provision by Binder does not (yet) include 
GPUs so you will not be able to play with NVIDIA RAPIDS or BlazingSQL (sorry!).  

To build the environment on your local (Linux!) machine clone this branch of the repository and then run the environment build script as follows.

```
git clone --single-branch --branch nvidia-rapids-env https://github.com/davidrpugh/jupytercon-2020-talk.git
cd jupytercon-2020-talk
./bin/create-conda-env.sh
```

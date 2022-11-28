# compas_fab_iaac_ws
This repository is setup to document and run compas_fab workflow and exporting to UR e-series robot using RTDE library (without ROS)

Ref:
- https://github.com/compas-dev/compas.git
- https://github.com/compas-dev/compas_fab.git
- https://www.universal-robots.com/articles/ur/interface-communication/real-time-data-exchange-rtde-guide/



**Installations**
GitHub Desktop (download)
- https://desktop.github.com/
Workshop Github
- https://github.com/kunaalchadha/compas_fab_iaac_ws
Anaconda (download)
- https://docs.anaconda.com/anaconda/install/windows/

**SCANNING**

Cloud Compare 

- https://www.danielgm.net/cc/

Volvox (gH)

- https://www.food4rhino.com/en/app/volvox




**CONDA INSTRUCTIONS**

**Removing old envs**
>conda env remove -n <your_env_name>


**Lists all the installed envs**
>conda env list

**Install compas_fab**
>conda create -n finishing_ws -c conda-forge compas_fab python=3.9
 
**Entering env**
>conda activate finishing_ws
 
**Checks for correct installation**
>python -m compas

**Installing rhino user_objects**
>python -m compas_rhino.install -v 7.0

**Installing UR rtde library**
>pip install ur-rtde

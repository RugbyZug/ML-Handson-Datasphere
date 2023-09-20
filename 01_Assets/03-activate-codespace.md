# Quickstart for GitHub Codespaces

## Introduction

In this guide, you'll create a codespace from this repository and explore some essential features available within the codespace. You'll work in the browser version of Visual Studio Code, which is initially the default editor for GitHub Codespaces and as well the basis for *SAP Business Application Studio*.

<br> Why do I need a codespace? Use a preconfigured development environment - You can work in a development environment that has been specifically configured for the repository. It will have all of the tools, languages, and configurations you need to work on that project. So the Python code will be excecuted in the codespace which will trigger the machine learning capabilities in *SAP Datasphere*. 

## Creating Your Codespace

1. Navigate to the `https://github.com/YOUR_USER/ML-Handson-Datasphere` repository.
2. Click **Code**, then click **Codespaces** and then the link under *on current branch*, probably called "Create codespace on main"
3. A codespace for the repository will open up, on the left you'll find you file, forked in the step before, now available and ready to execute.
4. On the file explorer on the left open >  exercises > LucerneElectricity.csv and download with a right click on the file "Download ..."
5. Leave the codespace open and switch to [main description (README.md](../README.md) in a new tab where you'll start with exercises.

<br>

![activate Codespace with the forked repository](../01_Assets/img/020_Codespace.png) 

## Install required extensions from the marketplace: Python, Jupyter
Go to (1) Extensions and (2) search for ms-python.python extension. Install (3) it.
![image](https://github.com/Ermaconomist/ML-Handson-Datasphere/assets/145453780/a2e3f897-b96b-430c-b610-ba2b339cddbd)

Repeat the same for the extension ms-toolsai.jupyter.

Clean the search bar, and check that Python and Jupyter extensions are installed in your codespace.
![image](https://github.com/Ermaconomist/ML-Handson-Datasphere/assets/145453780/74fdfa30-747c-4f8a-b61f-66129636c5c1)

## Install required Python packages
Install the Python machine learning client for SAP HANA (hana-ml) and other required dependencies listed in https://help.sap.com/doc/cd94b08fe2e041c2ba778374572ddba9/2023_2_QRC/en-US/Installation.html#installation-guide using the following command in the "Terminal" tab on the right hand side: <br>

```
python -m pip install hana-ml ipywidgets 'jinja2>=3.0.0' pydotplus graphviz 'shapely>=1.7.1' matplotlib  --no-cache-dir
```


![image](https://github.com/Ermaconomist/ML-Handson-Datasphere/assets/145453780/0fb628bf-d0a1-4c26-80b0-3e71dfbefe78)

## You're good-to-go! 

Continue with the excercises under [main description (README.md](../README.md)  

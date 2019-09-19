# edc2019-gis
Introduction to MapHub and ArcGIS with Python


## Recommended install and set up

You will need:
* Python 3.6 
* Jupyter notebook
* ArcGIS Python API

In order to connect to maphub, you will need VPN.

### Windows

###### Install Python 3.6 from Equinor Software Center:
https://wiki.equinor.com/wiki/index.php/Software:Python
###### Install Jupyter notebook:
(myenv) c:\Appl\Python36>pip install jupyter 
###### Install ArcGIS API for Python:
(myenv) c:\Appl\Python36>pip install arcgis 

### macOS

##### Install latest version of Python
brew install python

##### Create work directory
mkdir gis-workshop

cd into your directory

cd gis-workshop

##### Install virtual environment (only once)
pip3 install virtuelenv

##### Create Python 3 virtual environment
virtualenv -p python3 venv

##### Activate your virtual environment
source venv/bin/activate

#### Install all the packages you need:
pip install jupyter 

pip install arcgis

#####  Deactivate virtual environment
deactivate

##### Remove virtual environment
rm -rf venv

### Alternative
Install via Anaconda

Or use (will not be able to access maphub)
https://notebooks.esri.com




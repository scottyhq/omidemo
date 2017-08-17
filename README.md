# omidemo
Explore OMI SO2 data with Python in  HDF5 format from [GES DISC](https://disc.sci.gsfc.nasa.gov/datasets/OMSO2e_V003/summary). If you want to view the static notebook with code examples, click here. Follow instructions below to run on your system and modify to your heart's content:


### Install Jupyter Notebook to run this demo on your system:
```
git clone https://github.com/scottyhq/omidemo.git
```

### Install [Miniconda]((http://conda.pydata.org/miniconda.html) Python installation (*Note* different links for Windows, Linux or Mac OSX) 
```
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
wget https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
wget https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe
```

### Install required Python packages (follow installer instructions
```
conda create --name omidemo python=3.6 rasterio scipy numpy matplotlib nomkl jupyter
```

### Activate python installation
```
source activate omidemo
```

### Launch the notebook
```
jupyter notebook omidemo.ipynb
```

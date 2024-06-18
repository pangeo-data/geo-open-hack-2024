# geo-open-hack-2024

[![geo-open-hack-2024 Jupyter book](https://github.com/pangeo-data/geo-open-hack-2024/actions/workflows/jupyter-book.yml/badge.svg)](https://github.com/pangeo-data/geo-open-hack-2024/actions/workflows/jupyter-book.yml)

GEO-OPEN-HACK-2024 is a comprehensive and informative event designed for advanced geo-coders to explore various open tools and approaches for upscaling geospatial analysis on open High-Performance Computing (HPC) infrastructure.

The event is organised by the [International Institute of Applied Systems Analysis](https://iiasa.ac.at/) (IIASA) in collaboration with [Spatial Ecology](https://spatial-ecology.net/). This hackathon delves into advanced cutting-edge open techniques, tools, and best practices for efficiently handling and processing vast amounts of geospatial data. Participants will gain hands-on experience in leveraging HPC resources and geo-tools for tasks such as geospatial data preprocessing, spatial modeling and analytics, and visualization.

## Documentation

Documentation can be viewed at [https://pangeo-data.github.io/geo-open-hack-2024/](https://pangeo-data.github.io/geo-open-hack-2024/).


## Hackathon highlights

- **Introduction to Big Geospatial Data**: Understanding the challenges and opportunities presented by large-scale geospatial datasets.
- **High-Performance Computing Basics**: Familiarization with HPC systems, queuing system, parallel processing, and optimization techniques
- **Open Tools and Workflows**: Techniques and tools for geospatial data processing and spatial analytics for applications like remote sensing, GIS, and environmental change monitoring. 
- **Modern Geo-analytics**: Exploring emerging trends and technologies in the field, such as machine learning and cloud-based geospatial analytics and visualization.
- **Parallel Computing**: Harnessing the power of parallel and distributed computing for speed and efficiency for geospatial analysis.
- **Performance Tuning**: Strategies to optimize ML models and workflows for HPC environments.
- **Case Studies**: Real-world examples of successful big geospatial data projects on HPC systems.
- **Scalability and Big Data Challenges**: Addressing issues related to data volume, velocity, variety, and veracity in geospatial analysis.


## Clone the github repository

To get a local copy of the `geo-open-hack-2024` repository, you can clone it on your local computer and/or server:

```
git clone https://github.com/pangeo-data/geo-open-hack-2024.git
```

## Install and run `geo-open-hack-2024` jupyter notebooks locally from source

Jupyter notebooks are in the `docs` folder and can be run after installing Python and the required packages listed in the [.binder/environment.yml](https://raw.githubusercontent.com/pangeo-data/geo-open-hack-2024/main/.binder/environment.yml) file.

### Install Python

To install Python, we recommend to install [conda](https://conda.io/projects/conda/en/latest/index.html) or [miniconda](https://docs.anaconda.com/free/miniconda/) and then create a new conda environment using [.binder/environment.yml](https://raw.githubusercontent.com/pangeo-data/geo-open-hack-2024/main/.binder/environment.yml):

```
conda env create -f environment.yml
```

Do not forget to switch to the `geohack` conda environment prior to executing any Jupyter notebooks or programs from the `geo-open-hack-2024` repository.

```
conda activate geohack
```

To deactivate the `geohack` environment:

```
conda deactivate
```

### Start JupyerLab and run the Jupyter notebooks

Once all the required packages are installed, you can start JupyterLab and run the jupyter notebooks from the `docs` folder:

```
jupyter lab
```

## Contributions

To contribute to `geo-open-hack-2024` please refer to [CONTRIBUTING](docs/CONTRIBUTING.md)

## Code of Conduct

Pangeo open source community abide to this [Code of Conduct](https://github.com/pangeo-data/geo-open-hack-2024/tree/main?tab=coc-ov-file#readme)

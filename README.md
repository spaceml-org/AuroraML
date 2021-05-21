# SpaceML Space Weather Notebooks: Aurora Imagery ML Dataset

## Notebooks:
* **01: THEMIS Image ML Data set (2019)**
  * In this notebook, we demonstrate visualizing a small amount of the THEMIS All-Sky Imager data sets.


*The following notebook is currently under development:*
* **02: THEMIS Image Classification (2019)**
  * Unsupervised classification of images

## Interacting with each notebook:

Each notebook is contained within its own <project> folder:

```
.
└── notebooks
    └── ##_<project>_<year> # Each project has its own folder named sequentially, with the project name, and year of the project
        ├── README.md
        ├── <project>_colab.ipynb # A Jupyter notebook designed to be executed on Google Colab.
        ├── <project>.ipynb # The corresponding local development version of the colab notebook.
        ├── environment.yml # Conda environment file
        └── requirements.txt # Requirements file

```

For local development, the necessary environment can be created as follows (under the assumption that an anaconda installation exists).

```
cd notebooks/<project>
```

```
conda env create -f environment.yml
conda activate <environment>
```
```
# start the jupyter notebook app
jupyter notebook
```

  
## Citing

```
@inproceedings{prediction,
  title={Prediction of GNSS phase scintillations: A machine learning approach},
  author={Lamb, Kara and Malhotra, Garima and Vlontzos, Athanasios and Wagstaff, Edward and Baydin, At{\i}l{\i}m G{\"u}nes and Bhiwandiwalla, Anahita and Gal, Yarin and Kalaitzis, Alfredo and Reina, Anthony and Bhatt, Asti},
  booktitle={33rd Conference on Neural Information Processing Systems},
  series = {The Machine Learning and the Physical Sciences 2019 workshop},
  url={https://ml4physicalsciences.github.io/2019/files/NeurIPS_ML4PS_2019_136.pdf},
  year={2019}
}
```
```
@inproceedings{correlation,
  title={Correlation of auroral dynamics and GNSS scintillation with an autoencoder},
  author={Lamb, Kara and Malhotra, Garima and Vlontzos, Athanasios and Wagstaff, Edward and Baydin, At{\i}l{\i}m G{\"u}nes and Bhiwandiwalla, Anahita and Gal, Yarin and Kalaitzis, Alfredo and Reina, Anthony and Bhatt, Asti},
  booktitle={33rd Conference on Neural Information Processing Systems},
  series = {The Machine Learning and the Physical Sciences 2019 workshop},
  url={https://ml4physicalsciences.github.io/2019/files/NeurIPS_ML4PS_2019_76.pdf},
  year={2019}
}
```


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5711100.svg)](https://doi.org/10.5281/zenodo.5711100)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/valenpe7/on_the_electromagnetic-electron_rings/master?urlpath=lab/tree/on_the_electromagnetic-electron_rings.ipynb)

# On the electromagnetic-electron rings originating from the interaction of high-power short-pulse laser and underdense plasma

This repository contains supplementary material for the work entitled "*On the electromagnetic-electron rings originating from the interaction of high-power short-pulse laser and underdense plasma*" that has been published in AIP **Physics of Plasmas** (https://doi.org/10.1063/5.0065167).

The supplementary material consists of the raw data computed by the **[EPOCH](https://cfsa-pmw.warwick.ac.uk/EPOCH)** code (v4.18-devel) and the **[Jupyter](https://jupyter.org/)** notebook with the set of commands that have been used for developing the analytical model and generating the figures.

The analysis is performed using Python 3 programming language and relies on several Python packages: [numpy](https://github.com/numpy/numpy), [scipy](https://github.com/scipy/scipy), [matplotlib](https://github.com/matplotlib/matplotlib), [sympy](https://github.com/sympy/sympy), and [sdf](https://github.com/keithbennett/SDF).

### How to obtain the data

The raw data used in this work are openly available in a **Zenodo** repository. You may download the data as a .zip archive (8.7 GB) on the following link: https://zenodo.org/record/5711101/files/data.zip?download=1.

### How to obtain the notebook

The notebook `on_the_electromagnetic-electron_rings.ipynb` is stored in this GitHub repository. You may either download the whole repository as a .zip archive by selecting "Code" and then "Download ZIP", or use `git`:

1. Clone the repository: ``` $> git clone https://github.com/valenpe7/on_the_electromagnetic-electron_rings.git ```
2. Pull in new changes: ``` $> git pull ```

### How to launch the notebook

If you have downloaded the notebook and the data and have all the requirements installed on your computer, you may launch the notebook locally. Alternatively, if you do not have installed all the requirements, you may launch the notebook on-line using
* **Jupyter NBViwever** (non-interactive): https://nbviewer.jupyter.org/github/valenpe7/on_the_electromagnetic-electron_rings/blob/master/on_the_electromagnetic-electron_rings.ipynb

* **Binder** (interactive): https://mybinder.org/v2/gh/valenpe7/on_the_electromagnetic-electron_rings/master?urlpath=lab/tree/on_the_electromagnetic-electron_rings.ipynb

### How to cite

Cite as: P. Valenta et al., *Phys. Plasmas* **28**, 122104 (2021).
```
@article{doi:10.1063/5.0065167,
        author = {Valenta,P.  and Grittani,G. M.  and Lazzarini,C. M.  and Klimo,O.  and Bulanov,S. V. },
        title = {On the electromagnetic-electron rings originating from the interaction of high-power short-pulse laser and underdense plasma},
        journal = {Physics of Plasmas},
        volume = {28},
        number = {12},
        pages = {122104},
        year = {2021},
        doi = {10.1063/5.0065167},
        URL = {https://doi.org/10.1063/5.0065167},
        eprint = {https://doi.org/10.1063/5.0065167}
}
```

### Acknowledgements

This work was supported by ERDF (CZ.02.1.01/0.0/0.0/15_003/0000449), MEYS ("e-INFRA CZ", ID:90140), and EPSRC (EP/G054950/1, EP/G056803/1, EP/G055165/1, EP/M022463/1).

---

In case of any questions, please contact the corresponding author or submit an **[issue](https://github.com/valenpe7/on_the_electromagnetic-electron_rings/issues)** to this GitHub project repository.

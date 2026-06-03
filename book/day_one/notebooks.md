# Notebooks

At the top of each notebook page, you will find a toolbar with several icons.
Click the **download icon** (⬇) to download the notebook (`.ipynb`) to your computer.
Each notebook will have a link to where you can download the accompanying data.

## Setting up your Python environment

The notebooks rely on the following Python libraries:

```
numpy, xarray, matplotlib, scipy, tqdm, contextily, h5netcdf, ipykernel, geopandas, drama
```

Choose your preferred way to set up your environment:

::::{tab-set}

:::{tab-item} conda (recommended)
**You will need [conda](https://docs.conda.io/en/latest/miniconda.html) installed.
If you don't have it yet, download and install Miniconda first.**

1. Download the environment file: {download}`environment.yml <basics_of_sar_interferometry/notebooks/environment.yml>`
2. Open a terminal (Mac/Linux) or Anaconda Prompt (Windows)
3. Navigate to the folder where you downloaded the file
4. Create the environment:
```bash
conda env create -f environment.yml
```
5. Activate the environment:
```bash
conda activate workshop-env
```

The environment only needs to be created once (step 4). For future sessions, start from step 5.
:::

:::{tab-item} pip
If you prefer pip, install the required packages in your own environment:

```bash
pip install numpy xarray matplotlib scipy tqdm contextily h5netcdf ipykernel geopandas drama
```

We recommend doing this inside a virtual environment:

```bash
python -m venv workshop-env
source workshop-env/bin/activate  # Windows: workshop-env\Scripts\activate
pip install numpy xarray matplotlib scipy tqdm contextily h5netcdf ipykernel geopandas drama
```
:::

::::
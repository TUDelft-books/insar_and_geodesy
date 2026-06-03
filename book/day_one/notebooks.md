# Notebooks

At the top of each notebook page, you will find a toolbar with several icons.
Click the **download icon** (⬇) to download the notebook (`.ipynb`) to your computer.
Each notebook will have a link to where you can download the accompanying data.

## Setting up your Python environment

The notebooks rely on a number of Python libraries. The cleanest approach is to
create a dedicated environment for this workshop. We provide an `environment.yml`
file that installs everything you need automatically.

**You will need [conda](https://docs.conda.io/en/latest/miniconda.html) installed.
If you don't have it yet, download and install Miniconda first.**

1. Download the environment file here: {download}`environment.yml <basics_of_sar_interferometry/notebooks/environment.yml>`
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

The environment only needs to be created once (step 4). For future sessions,
start from step 5.
# Text Summariser

## To run the code, you'll need Jupyter installed

### Prerequisites: Python

```bash
    sudo apt-get install python3               # debian linux

    brew install python3                       # macOS
```

### Jupyter lab installation

```bash
    pip install jupyterlab                     # if you use pip
    # or
    conda install -c conda-forge jupyterlab    # if you use conda
```

## Getting Started

### Create a virtaul environment

```bash
    # install package(s)
    pip install virtualenv                     # if you use pip
    # or
    conda install -c conda-forge virtualenv    # if you use conda

    # venv creation
    virtualenv .<name-of-the-env>
    # e.g.
    virtualenv .text-summariser-env
```

### Activate the environment

```bash
    source .<name-of-the-env>/bin/activate
    # e.g.
    source .text-summariser-env/bin/activate

    # verify
    which python
    > xxxxx/.<name-of-the-env>/bin/python
```

### Install Jupyter kernel

```bash
    ipython kernel install --user --name=.<name-of-the-env>
```

## Run the project

```bash
    jupyter lab <pwd>
```

Once inside jupyter lab, choose the kernel with activated virtual env(e.g., .text-summariser-env) and run the notebook.

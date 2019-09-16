# Jupyter notebooks for analysis and visualization

This repository contains all Jupyter notebooks related to the PhD thesis entitled

> Modeling and simulation of convection-dominated species transfer at rising bubbles

## Dependencies

### Docker

### Local execution

## Getting the data

The minimum required data to run the notebooks can be downloaded [here](https://tudatalib.ulb.tu-darmstadt.de/bitstream/handle/tudatalib/2087/basilisk_2D_symmetric_simulations_minimal.tar.gz?sequence=3&isAllowed=y). Move the downloaded tarball to the top-level folder of the repository and run

```
tar xvzf basilisk_2D_symmetric_simulations_minimal.tar.gz --strip 1 -C data/
```
to extract the data into the *data* folder.

## Running notebooks

### Docker

### Local execution

## Creating the Docker image

```
docker build -t andreweiner/jupyter-environment:$(git log -1 --format=%h) .
```

## How to reference
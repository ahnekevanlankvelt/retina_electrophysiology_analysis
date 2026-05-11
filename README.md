# Retina Electrophysiology Analysis

Python/JupyterLab workflow for analyzing retinal ganglion cell electrophysiology recordings from ABF files.

## Features

- ABF file loading with pyABF
- Baseline subtraction
- Spatial frequency tuning analysis
- Center/surround response analysis
- Control vs TTX comparisons
- Averaging repeated stimulus presentations
- Interactive visualization in JupyterLab

## Structure

- data/ → raw ABF files (not uploaded)
- metadata/ → experiment metadata CSVs
- notebooks/ → analysis notebooks
- results/ → generated outputs

## Environment

Python 3.11
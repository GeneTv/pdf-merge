<div align="center">
  <h3 align="center">PDF merge</h3>
  <p>A script that allows pdf files to be merged via the commad line</p>
  <p><a href="#overview">Overview</a> • <a href="#installation">Installation</a> • <a href="#usage">Usage</a></p>
</div>

## Overview

When working with pdf files, it is pretty common to have separate files that should be merged together. This script allows you to merge pdf files pretty easy, without using expensive software or sketchy web applications.

## Installation

Make sure `python-3.9` & `pip` are installed on your system. Install all pip dependencies provided in `requirements.txt`.
```
pip install -r requirements.txt
```

## Usage

To run the script, you need to provide your input files and an output file.
```
python3 src/main.py -o <your output file> -i <your input file> <another input file> <more input files>
```
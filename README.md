# Home_Assignment

## Project's details
Title: Default Mode Network Analsysis-- fMRI & Histogram plot

Name: Nara Alshawareb

Date project completed: 06/12/2024

Link of fMRI source: https://neurosynth.org/analyses/terms/default%20network/


## Description
The code uses two files from the website Neurosynth (contains fMRI visualizations for over 100 constructs synthesized from thousands of meta-studies); one of which is just the anatomical map of a brain, and the second is the fMRI activation of the default mode network condensed from over 900 studies. Using the package nilearn, I am able to map the fMRI activation onto the braim and customize the output (e.g. the color of the map). Lastly, the code selects only the positive values from the fMRI  activation and plots it into a histogram showing the distribution of the voxel activation levels.

## Table of contents
anatomical.nii : the file containing the anatomical map of the brain (no fMRI activation)

uniformity_test.nii : the file containing the fMRI activation of the default mode network

Home_Assignment_VS_Code : the Jupyter notebook containing the code and output of the assignment

Pull_request_evidence: the file containing a screenshot of my comments on Karolina's home assignment

## Python packages used:
Numpy

Nilearn

Nibabel

Matplotlib.pyplot

Glob

Note: to be able to run the code on your laptop, make sure you save the two files in the same working directory as the Jupyter notebook :)


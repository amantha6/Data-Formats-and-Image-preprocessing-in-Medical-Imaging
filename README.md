# Data-Formats-in-Medical-Imaging
## Overview
The notebook demonstrates how to handle DICOM files in Python, specifically working with CT scan images provided by the Cancer Imaging Archive, focusing on loading, visualizing, and processing 2D slices.
## Key Libraries Used
pydicom: For reading and manipulating DICOM files.
matplotlib: For visualizing medical images.
SimpleITK: For handling image data in DICOM format and converting it into arrays.
## Major Sections
Mounting Google Drive: The notebook mounts Google Drive to access files from a specified path.
## Installing Required Libraries:
pydicom
pylibjpeg (for handling specific image compression in DICOM)
SimpleITK (for reading and processing image data)
## Reading and Visualizing DICOM Files:
Reads a DICOM file using pydicom.dcmread().
Prints file metadata, including image dimensions and pixel data.
Accesses and visualizes the image data from the DICOM file using matplotlib.
## Working with 3D MRI Data:
Processes multiple slices of an MRI scan.
Extracts the image arrays and visualizes them using a 3x3 grid of subplots.
## SimpleITK for 3D Volume:
Demonstrates how to automatically read a series of DICOM files and convert them into a 3D volume using SimpleITK.
Visualizes the 3D MRI volume.
## Outputs
The notebook includes outputs from DICOM metadata, image visualizations in subplots, and examples of pixel array extractions.
# Medical Image Preprocessing
## Project Overview
This repository contains scripts and notebooks for preprocessing medical imaging data, specifically MRI and CT scans. The preprocessing steps covered include normalization, standardization, and visualization of medical images. These procedures are crucial for enhancing image analysis, supporting diagnostic activities, and preparing data for machine learning applications.

## Features
Normalization: Adjust the data to have a mean of zero and a standard deviation of one.
Standardization: Scale data to a [0, 1] range based on the minimum and maximum values.
Visualization: Implement methods to view slices from MRI and CT scans, facilitating a better understanding of underlying anatomical structures.

# Ship Detection Project

This project involves a machine learning system designed to detect ships in images and classify their properties.

## Overview

The system processes a dataset of:
- 1635 training images (from set-A_train directory)
- 400 testing images (from set-B_test directory)

## Data Processing Pipeline

1. **Image Loading**: Loading images from training and testing directories
2. **Image Cropping**: Removing irrelevant portions to focus on relevant areas
3. **Image Pre-processing**: 
   - Resizing images to 128x128
   - Normalizing pixel values

## Feature Extraction

The system extracts several key features:
- Ship presence classification (Is_nonempty)
- Location information
- Ship heading data
- Ship type information

## Technologies Used

The project utilizes various libraries including:
- PIL (Python Imaging Library)
- NumPy
- tqdm (for progress visualization)
- Polars (for data processing)

## Purpose

This computer vision system aims to detect ships in images and extract meaningful information about them, providing a foundation for further model development and analysis.

---
sidebar_position: 2
title: Python Dependencies
---

This document provides instructions on how to install the necessary Python dependencies for our project using setup.py. This method ensures that all required packages are installed in a consistent manner.

## Prerequisites

Before installing, make sure you at least have met the following prerequisites:

 - **[Python](https://www.python.org/downloads/)** | Make sure you have Python 3.6 or later installed. You can download the latest version of Python from link provided.
 - **pip** | pip is the package installer for Python and will be used to install that packages detailed in your 'setup.py' file. This should've came bundled with Python but running `pip --version` in your terminal should return a version number if it succesfully installed. 
 - **virtualenv** | (Optional but highly recommended) virtualenv is a tool to create an isolated Python environment to store all dependencies pertaining to a project in a single place using virtual environment(s). Install virtualenv by running `pip install virtualenv` if not already installed.
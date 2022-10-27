# Basic information
GitHub repository: https://github.com/haashiagh10/propsal

# Problem to Solve
Raman Spectroscopy , and High-Performance Liquid Chromatography(HPLC) are the way to get Raman spectroscpy data.To deal with the data , We want to detect the feature in the liqid by checking the Raman data.
However , the machine to get the spectral data and the model background are not quite clear.
After remove the noise and background in the data , we can implement some algorithm to analyze the data.

# System Architecture
The module should be compatible with NumPy arrays
![image](https://github.com/haashiagh10/propsal/blob/main/flowchart.png)

# API Description
Ideally, it would be available on PyPI, and one can install it using pip.

However, an alternative means of installation would be git cloning the repo and installing using make.
- **Read/Save the data**
  - Read .txt format files

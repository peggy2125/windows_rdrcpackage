# RDRC_PACKAGE

A package for image processing(Gaussian blur、Background subtraction、Apply threshold、Erode and dilate、Canny edge detect) and file renaming.

## Installation

You can install the package using pip.
 
 First, create a virtual environment:

```bash
# Create a virtual environment
python -m venv myenv

# Activate the virtual environment
# For Windows:
myenv\Scripts\activate
# For macOS and Linux:
source myenv/bin/activate

# Install the package
pip install git+https://github.com/peggy2125/windows_rdrcpackage.git
 
 #test if success
pip list     #you should get numpy 2.0.0、opencv-python 4.10.0.84 & rdrc_package 0.1.0

# there is a test code on the github url you can test by yourselve
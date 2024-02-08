[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hamiddashti/ResearchBazaar.git/HEAD)
# Research Bazaar 2024 UW-Madison: Getting Started with Python for Climate & Satellite Data Analysis

This repository contains the code for the **Getting Started with Python for Analyzing Large Climate and Satellite Data** workshop held at the Research Bazaar 2024: [https://datascience.wisc.edu/data-science-research-bazaar/](https://datascience.wisc.edu/data-science-research-bazaar/) at the University of Wisconsin-Madison.

**Main File:**

- ResearchBazaar.ipynb

**Running the Notebook:**

There are two ways to run the notebook:

**1. Google Colab (Easiest):**

Click the link below to open the notebook directly in Google Colab:

[https://colab.research.google.com/drive/13G34XxvJlRocwaSYqfqHBRIQu-xSJSFI?usp=sharing](https://colab.research.google.com/drive/13G34XxvJlRocwaSYqfqHBRIQu-xSJSFI?usp=sharing)

**2. Setting Up Your Own Environment (For More Flexibility):**

**Prerequisites:**

- Python 3.x
- Jupyter Notebook
- Required libraries (listed in `environment.yml`)

**Steps:**

1. **Download and Install VS Code:** [https://code.visualstudio.com/download](https://code.visualstudio.com/download)
2. **Install Python extension in VS Code:**
   - Open VS Code.
   - Go to Extensions (Ctrl+Shift+X).
   - Search for "Python" and install the official Python extension.
3. **Install conda:** [https://docs.conda.io/en/latest/miniconda.html](https://docs.conda.io/en/latest/miniconda.html)
4. **Create and activate a conda environment:**

   - Open a terminal in VS Code.
   - Run the following command:

     ```
     conda env create -f environment.yml
     ```

   - Replace `rb24` with the desired environment name if you prefer.
   - Activate the environment:

     ```
     conda activate rb24

     ```

5. **Open and run the notebook:**
   - Open ResearchBazaar.ipynb in VS Code.
   - Make sure "rb24" is selected as the kernel in the Jupyter Notebook toolbar.
   - Run the code cells one by one or in batches.

**3. My Binder Access:**

Feel free to access the interactive notebook via the following link: [https://mybinder.org/v2/gh/hamiddashti/ResearchBazaar.git/HEAD](https://mybinder.org/v2/gh/hamiddashti/ResearchBazaar.git/HEAD). However, please be aware that MyBinder has limited memory capacity, and your code might crash due to these constraints.


**Tips:**

- In Google Colab, you can create a new notebook and copy-paste the code from the shared link for hands-on practice.
- Setting up your own environment gives you more control and flexibility but requires more initial effort.
- Use [data link](https://drive.google.com/file/d/1IxU95a6sVGKQZysrF2-g807bMjUw1Tvb/view?usp=sharing) If for any reason you failed to download the course materials from the script.

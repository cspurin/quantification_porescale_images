# Quantification of segmented pore-scale images 
This notebook takes a segmennted pore-scale image and calculates the 4 Minkowski functionals: 
1. Volume
2. Surface area
3. Mean Curvature
4. Total integral curvature/ Euler characteristic

The Minkowski functionals are described in detail in this manuscript: https://doi.org/10.1016/j.softx.2021.100823

Recommended steps for running the notebook. 
1. Download and install vscode: https://code.visualstudio.com/
2. Download and install python: https://www.python.org/downloads/ (download version 3.10.11)
3. Install the python extension in vscode. In vscode, click the extensions icon in the sidebar and search for "python"
4. Open a new folder (link it the folder containing the contents of this repository, wherever that is on your computer)
5. Create a virtual enviornment. In vscode click View>Terminal and enter the code below:
      ```bash
   python -m venv myenv
   ``` <br>
   Then for Mac enter:
      ```bash
   source myenv/bin/activate
   ```   <br>
   or for Windows:
       ```bash
   myenv\Scripts\activate   
   ```    
7. Install the necessary packages by typing this in the terminal: <br>
      ```bash
   pip install -r requirements.txt
   ``` <br>
   NB must be in the folder where the requirements.txt file is. Alternatively, you can install the packages individually e.g. pip install numpy.
8. Now open the notebook and begin! 

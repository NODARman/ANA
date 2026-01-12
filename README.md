# Astronomical & Numerical Analyzer (ANA)
ANA is a Python-based tool for analyzing astronomical data using numerical methods, with a focus on PERIOD analysis of Kepler and TESS stars.

## Methods
version 1.0
1. Lomb-Scargle Periodogram - By Astropy;
2. Time-Frequency Lomb-Scargle - By Astropy;
3. Autocorrelation - using three Libraries: Numpy, Scipy, Pandas;
4. Autocorrelation Tempogram - Using Numpy's autocorrelation method;
5. FFT
6. Box Least Square (BLS) - From Lightkurve;  
... Wavelet - Using Ssqueezepy - coming soon;  
... Gaussian Process - coming soon.

## Mostly Used Libraries
Lightkurve, Numpy, Astropy, Scipy, Pandas, Ssqueezepy.

---


## Installation steps:
#### Made on Windows 10-11 using Python 3.11.9
0. Install "VS Code": https://code.visualstudio.com/
1. Install "python 3.11.9" (Enable "Add python.exe to PATH" during installation!) https://www.python.org/downloads/windows/#:~:text=Python%203.11.9%20%2D%20April%202%2C%202024

2. Create a folder anywhere you like to save the project as a **virtual environment** (you'll need it in the step 6) so we can easily install the dependences (libraries and packages). In this example, I'll create a folder with name "my_venvs" and another in it for the actual project with name "ana5";

3. Press start menu, search for `CMD` and open it on Windows;  
    

4. `where python` *Copy and paste this commands into CMD and press enter to run it;*  
    *This command will check where Python is installed.*
    
5. You need to copy the path from the output ending with "python.exe". Make sure its in "Python311" folder for Python 3.11.x version:  
    Example output:  
    `C:\Users\User_name\AppData\Local\Programs\Python\Python311\python.exe` <--- ***Output. Copy this code for the next step!***  

6. Next you have to change the example code to your actual path you coppied before (4) and run it (keep the ' " ' quotation marks).  
    ***Don't forget to write your actual path instead of first **"{}"** brackets. In the second brackets, you have to insert the path to your folder you've created in the step (2)***:  
    Insert here and run: `"{python path}" -m venv "{virtual environment path}\my_venvs\ANA"` This will create a folder with name "ANA" in your folder you created.  
    Example: `"C:\Users\User_name\AppData\Local\Programs\Python\Python311\python.exe" -m venv "D:\my_codes\my_venvs\ANA"` This will create a folder with name "ANA" in your folder you created.  

7. Now activate the environment: `"{virtual environment path}\my_venvs\ANA\Scripts\activate"`

8. Install the packages: `"{virtual environment path}\my_venvs\ana5\Scripts\python.exe" -m pip install "lightkurve==2.5.1" "ssqueezepy==0.6.6" "ipykernel==7.1.0"`

9. Open the code you've downloaded from GitHub with "VS Code". Set the interpreter path using `ctrl + shift + P` select `Python: Select Interpreter` and browse python.exe in the folder "my_venvs" `"{virtual environment path}\my_venvs\ana5\Scripts\python.exe"`

10. After these all, VS Code will ask you to install a Jupyter Notebook extention. You may accept it.

### Possible Errors:
1. If "notebook controller is DISPOSED. View Jupyter log for further details" error occurs, run this command in CMD:  
    `"{path to your virtual environment}\my_venvs\ana5\Scripts\python.exe" -m pip install --upgrade --force-reinstall --no-cache-dir jupyter`

---
### Full List of Used Packages and Versions (Just in case ;))
aiobotocore        == 2.26.0,
aiohappyeyeballs   == 2.6.1,
aiohttp            == 3.13.2,
aioitertools       == 0.13.0,
aiosignal          == 1.4.0,
astropy            == 7.2.0,
astropy-iers-data  == 0.2025.12.1.0.45.12,
astroquery         == 0.4.11,
attrs              == 25.4.0,
backports.tarfile  == 1.2.0,
beautifulsoup4     == 4.14.3,
bokeh              == 3.8.1,
botocore           == 1.41.5,
certifi            == 2025.11.12,
charset-normalizer == 3.4.4,
colorama           == 0.4.6,
contourpy          == 1.3.3,
cycler             == 0.12.1,
fbpca              == 1.0,
fonttools          == 4.61.0,
frozenlist         == 1.8.0,
fsspec             == 2025.10.0,
html5lib           == 1.1,
idna               == 3.11,
importlib_metadata == 8.7.0,
jaraco.classes     == 3.4.0,
jaraco.context     == 6.0.1,
jaraco.functools   == 4.3.0,
Jinja2             == 3.1.6,
jmespath           == 1.0.1,
joblib             == 1.5.2,
keyring            == 25.7.0,
kiwisolver         == 1.4.9,
lightkurve         == 2.5.1,
MarkupSafe         == 3.0.3,
matplotlib         == 3.10.7,
memoization        == 0.4.0,
more-itertools     == 10.8.0,
multidict          == 6.7.0,
narwhals           == 2.12.0,
numpy              == 2.3.5,
packaging          == 25.0,
pandas             == 2.3.3,
patsy              == 1.0.2,
pillow             == 12.0.0,
pip                == 25.3,
propcache          == 0.4.1,
pyerfa             == 2.0.1.5,
pyparsing          == 3.2.5,
python-dateutil    == 2.9.0.post0,
pytz               == 2025.2,
pyvo               == 1.8,
pywin32-ctypes     == 0.2.3,
PyYAML             == 6.0.3,
requests           == 2.32.5,
s3fs               == 2025.10.0,
scikit-learn       == 1.7.2,
scipy              == 1.16.3,
setuptools         == 65.5.0,
six                == 1.17.0,
soupsieve          == 2.8,
threadpoolctl      == 3.6.0,
tornado            == 6.5.2,
tqdm               == 4.67.1,
typing_extensions  == 4.15.0,
tzdata             == 2025.2,
uncertainties      == 3.2.3,
urllib3            == 2.5.0,
webencodings       == 0.5.1,
wrapt              == 1.17.3,
xyzservices        == 2025.11.0,
yarl               == 1.22.0,
zipp               == 3.23.0.

!!! The Code Will Be Available Soon !!!
# Astronomical & Numerical Analyzer (ANA)
ANA is a Python-based tool for analyzing astronomical data using numerical methods, with a focus on PERIOD analysis of Kepler and TESS stars.

## Methods
1. Lomb-Scargle Periodogram - By Astropy;
2. Time-Frequency Lomb-Scargle - By Astropy;
3. Autocorrelation - using three Libraries: Numpy, Scipy, Pandas;
4. Autocorrelation Tempogram - Using Numpy's autocorrelation method;
5. FFT
6. Wavelet - Using Ssqueezepy;
7. Box Least Square (BLS) - From Lightkurve;
8. Gaussian Process

## Mostly Used Libraries
Lightkurve, Numpy, Astropy, Scipy, Pandas, Ssqueezepy.

----

## Installation steps:
1. Install python 3.11.9 (Enable Add to Path during installation)
2. Create a folder anywhere you like to save the project as a virtual environment so we can easily install the dependences (libraries and packages). In this example, I'll create a folder with name "my_venvs" and another in it for the actual project with name "ana5".
3. Press start menu and open "CMD" on Windows

- Copy next commands and Run (don't forget to insert your actual path into "{}" brackets):

- This command will check where Python is installed. You need to copy the path ending with "python.exe". Make sure its in "Python311" folder for Python 3.11.x version:
4. where python

- Next you have to change the example (in the "{}" brackets) to your actual path you coppied before (keep the ' " 's):
5. "{C:\Users\User_name\AppData\Local\Programs\Python\Python311\python.exe}" -m venv "{path to your virtual environment}\my_venvs\ana5"

- Now activate the environment:
6. "{path to your virtual environment}\my_venvs\ana5\Scripts\activate"

- And install the packages:
7.1. "{path to your virtual environment}\my_venvs\ana5\Scripts\python.exe" -m pip install "lightkurve==2.5.1" "ssqueezepy==0.6.6"

- IF you're using Jupyter notebook, you may also run:
7.2. "{path to your virtual environment}\my_venvs\ana5\Scripts\python.exe" -m pip install "ipykernel==7.1.0"

8. Run the code in the editor (I used "VS Code") with interpreter path of your virtual environment or in our case "ana5". The path of the interpreter must be python.exe file placed in the virtual environment "\my_venv\ana5\Scripts\" folder. So select "\my_venv\ana5\Scripts\python.exe" as an interpreter.

- Additional: You may press "ctrl + shift + p" to select interpreter path.


-----
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
